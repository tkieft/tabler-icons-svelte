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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-polaroid {classes}"
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
    <rect x="4" y="4" width="16" height="16" rx="2" />
    <line x1="4" y1="16" x2="20" y2="16" />
    <path d="M4 12l3 -3c.928 -.893 2.072 -.893 3 0l4 4" />
    <path d="M13 12l2 -2c.928 -.893 2.072 -.893 3 0l2 2" />
    <line x1="14" y1="7" x2="14.01" y2="7" />
</svg>
