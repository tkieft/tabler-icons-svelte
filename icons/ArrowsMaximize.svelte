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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-arrows-maximize {classes}"
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
    <polyline points="16 4 20 4 20 8" />
    <line x1="14" y1="10" x2="20" y2="4" />
    <polyline points="8 20 4 20 4 16" />
    <line x1="4" y1="20" x2="10" y2="14" />
    <polyline points="16 20 20 20 20 16" />
    <line x1="14" y1="14" x2="20" y2="20" />
    <polyline points="8 4 4 4 4 8" />
    <line x1="4" y1="4" x2="10" y2="10" />
</svg>
