<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    export let element = undefined;
    export let icon = true;
    let classes = "";
    export { classes as class };
</script>

<svg
    bind:this="{element}"
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-chart-arrows-vertical {classes}"
    width="{size}"
    height="{size}"
    viewBox="0 0 24 24"
    stroke="{color}"
    stroke-width="{strokeWidth}"
    fill="none"
    stroke-linecap="round"
    stroke-linejoin="round"
>
    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
    <path d="M18 21v-14" />
    <path d="M9 15l3 -3l3 3" />
    <path d="M15 10l3 -3l3 3" />
    <line x1="3" y1="21" x2="21" y2="21" />
    <line x1="12" y1="21" x2="12" y2="12" />
    <path d="M3 6l3 -3l3 3" />
    <path d="M6 21v-18" />
</svg>
