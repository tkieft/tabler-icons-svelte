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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-chart-arrows {classes}"
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
    <line x1="3" y1="18" x2="17" y2="18" />
    <path d="M9 9l3 3l-3 3" />
    <path d="M14 15l3 3l-3 3" />
    <line x1="3" y1="3" x2="3" y2="21" />
    <line x1="3" y1="12" x2="12" y2="12" />
    <path d="M18 3l3 3l-3 3" />
    <line x1="3" y1="6" x2="21" y2="6" />
</svg>
