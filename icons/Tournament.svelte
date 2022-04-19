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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-tournament {classes}"
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
    <path d="M5 4h4a1 1 0 0 1 1 1v4a1 1 0 0 1 -1 1h-4" />
    <path d="M5 14h4a1 1 0 0 1 1 1v4a1 1 0 0 1 -1 1h-4" />
    <path d="M10 7h4a1 1 0 0 1 1 1v8a1 1 0 0 1 -1 1h-4" />
    <line x1="15" y1="12" x2="20" y2="12" />
</svg>
