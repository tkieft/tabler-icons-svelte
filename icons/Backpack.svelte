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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-backpack {classes}"
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
    <path
        d="M11 7h2a6 6 0 0 1 6 6v6a1 1 0 0 1 -1 1h-12a1 1 0 0 1 -1 -1v-6a6 6 0 0 1 6 -6z"
    />
    <path d="M10 7v-1a2 2 0 1 1 4 0v1" />
    <path d="M10 15h4" />
</svg>
