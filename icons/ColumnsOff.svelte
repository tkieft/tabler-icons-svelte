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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-columns-off {classes}"
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
    <path d="M4 6h2" />
    <path d="M4 10h5.5" />
    <path d="M4 14h5.5" />
    <path d="M4 18h5.5" />
    <path d="M14.5 6h5.5" />
    <path d="M14.5 10h5.5" />
    <path d="M18 14h2" />
    <path d="M14.5 18h3.5" />
    <path d="M3 3l18 18" />
</svg>
