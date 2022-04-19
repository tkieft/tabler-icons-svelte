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
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-flag {classes}"
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
    <line x1="5" y1="5" x2="5" y2="21" />
    <line x1="19" y1="5" x2="19" y2="14" />
    <path d="M5 5a5 5 0 0 1 7 0a5 5 0 0 0 7 0" />
    <path d="M5 14a5 5 0 0 1 7 0a5 5 0 0 0 7 0" />
</svg>
