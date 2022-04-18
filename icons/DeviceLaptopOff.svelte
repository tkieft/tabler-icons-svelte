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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-device-laptop-off {classes}"
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
    <path d="M3 19h16" />
    <path
        d="M10 6h8a1 1 0 0 1 1 1v8m-3 1h-10a1 1 0 0 1 -1 -1v-8a1 1 0 0 1 1 -1"
    />
    <path d="M3 3l18 18" />
</svg>
