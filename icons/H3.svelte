<script>
    export let size = 24;
    export let color = "currentColor";
    export let fill = "none";
    export let strokeWidth = 2;
    export let element = undefined;
    export let icon = true;
    let classes = "";
    export { classes as class };
</script>

<svg
    bind:this="{element}"
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-h-3 {classes}"
    width="{size}"
    height="{size}"
    viewBox="0 0 24 24"
    stroke="{color}"
    stroke-width="{strokeWidth}"
    fill="{fill}"
    stroke-linecap="round"
    stroke-linejoin="round"
>
    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
    <path d="M19 14a2 2 0 1 0 -2 -2" />
    <path d="M17 16a2 2 0 1 0 2 -2" />
    <path d="M4 6v12" />
    <path d="M12 6v12" />
    <path d="M11 18h2" />
    <path d="M3 18h2" />
    <path d="M4 12h8" />
    <path d="M3 6h2" />
    <path d="M11 6h2" />
</svg>
