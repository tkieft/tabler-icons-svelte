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
    on:click
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-3d-rotate {classes}"
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
    <path d="M7 15.5l4 -2.5" />
    <path d="M3 13l4 2.5v4.5l4 -2.5v-4.5l-4 -2.5z" />
    <path d="M3 13v4.5l4 2.5" />
    <path d="M11 4a7 7 0 0 1 7 7v4l-3 -3" />
    <path d="M21 12l-3 3" />
</svg>
