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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-microscope {classes}"
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
    <path d="M5 21h14" />
    <path d="M6 18h2" />
    <path d="M7 18v3" />
    <path d="M9 11l3 3l6 -6l-3 -3z" />
    <path d="M10.5 12.5l-1.5 1.5" />
    <path d="M17 3l3 3" />
    <path d="M12 21a6 6 0 0 0 3.715 -10.712" />
</svg>
