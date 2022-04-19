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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-columns {classes}"
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
    <line x1="4" y1="6" x2="9.5" y2="6" />
    <line x1="4" y1="10" x2="9.5" y2="10" />
    <line x1="4" y1="14" x2="9.5" y2="14" />
    <line x1="4" y1="18" x2="9.5" y2="18" />
    <line x1="14.5" y1="6" x2="20" y2="6" />
    <line x1="14.5" y1="10" x2="20" y2="10" />
    <line x1="14.5" y1="14" x2="20" y2="14" />
    <line x1="14.5" y1="18" x2="20" y2="18" />
</svg>
