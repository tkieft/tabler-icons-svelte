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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-eyeglass {classes}"
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
    <path d="M8 4h-2l-3 10" />
    <path d="M16 4h2l3 10" />
    <line x1="10" y1="16" x2="14" y2="16" />
    <path d="M21 16.5a3.5 3.5 0 0 1 -7 0v-2.5h7v2.5" />
    <path d="M10 16.5a3.5 3.5 0 0 1 -7 0v-2.5h7v2.5" />
</svg>
