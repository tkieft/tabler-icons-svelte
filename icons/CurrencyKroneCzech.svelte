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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-currency-krone-czech {classes}"
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
    <path d="M5 6v12" />
    <path d="M5 12c3.5 0 6 -3 6 -6" />
    <path d="M5 12c3.5 0 6 3 6 6" />
    <path d="M19 6l-2 2l-2 -2" />
    <path d="M19 12h-2a3 3 0 0 0 0 6h2" />
</svg>
