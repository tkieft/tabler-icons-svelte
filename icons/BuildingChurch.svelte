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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-building-church {classes}"
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
    <line x1="3" y1="21" x2="21" y2="21" />
    <path d="M10 21v-4a2 2 0 0 1 4 0v4" />
    <line x1="10" y1="5" x2="14" y2="5" />
    <line x1="12" y1="3" x2="12" y2="8" />
    <path d="M6 21v-7m-2 2l8 -8l8 8m-2 -2v7" />
</svg>
