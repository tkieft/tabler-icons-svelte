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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-arrows-minimize {classes}"
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
    <polyline points="5 9 9 9 9 5" />
    <line x1="3" y1="3" x2="9" y2="9" />
    <polyline points="5 15 9 15 9 19" />
    <line x1="3" y1="21" x2="9" y2="15" />
    <polyline points="19 9 15 9 15 5" />
    <line x1="15" y1="9" x2="21" y2="3" />
    <polyline points="19 15 15 15 15 19" />
    <line x1="15" y1="15" x2="21" y2="21" />
</svg>
