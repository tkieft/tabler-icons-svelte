<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    export let icon = true;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-switch {classes}"
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
    <polyline points="15 4 19 4 19 8" />
    <line x1="14.75" y1="9.25" x2="19" y2="4" />
    <line x1="5" y1="19" x2="9" y2="15" />
    <polyline points="15 19 19 19 19 15" />
    <line x1="5" y1="5" x2="19" y2="19" />
</svg>
