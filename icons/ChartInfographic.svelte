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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-chart-infographic {classes}"
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
    <circle cx="7" cy="7" r="4" />
    <path d="M7 3v4h4" />
    <line x1="9" y1="17" x2="9" y2="21" />
    <line x1="17" y1="14" x2="17" y2="21" />
    <line x1="13" y1="13" x2="13" y2="21" />
    <line x1="21" y1="12" x2="21" y2="21" />
</svg>
