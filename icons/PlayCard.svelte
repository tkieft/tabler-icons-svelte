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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-play-card {classes}"
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
    <rect
        transform="rotate(90 12 12)"
        x="3"
        y="5"
        width="18"
        height="14"
        rx="2"
    />
    <line x1="8" y1="6" x2="8.01" y2="6" />
    <line x1="16" y1="18" x2="16.01" y2="18" />
    <path d="M12 16l-3 -4l3 -4l3 4z" />
</svg>
