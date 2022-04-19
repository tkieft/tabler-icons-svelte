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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-adjustments-off {classes}"
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
    <circle cx="6" cy="10" r="2" />
    <path d="M6 6v2" />
    <path d="M6 12v8" />
    <circle cx="12" cy="16" r="2" />
    <path d="M12 4v4" />
    <path d="M12 12v2" />
    <path d="M12 18v2" />
    <circle cx="18" cy="7" r="2" />
    <path d="M18 4v1" />
    <path d="M18 9v5" />
    <path d="M18 18v2" />
    <path d="M3 3l18 18" />
</svg>
