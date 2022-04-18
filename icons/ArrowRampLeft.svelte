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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-arrow-ramp-left {classes}"
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
    <line x1="17" y1="3" x2="17" y2="11.707" />
    <path d="M13 7l4 -4l4 4" />
    <path d="M7 14l-4 -4l4 -4" />
    <path d="M17 21a11 11 0 0 0 -11 -11h-3" />
</svg>
