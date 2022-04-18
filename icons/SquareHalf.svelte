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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-square-half {classes}"
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
    <path d="M12 4v16" />
    <rect x="4" y="4" width="16" height="16" rx="2" />
    <path d="M12 13l7.5 -7.5" />
    <path d="M12 18l8 -8" />
    <path d="M15 20l5 -5" />
    <path d="M12 8l4 -4" />
</svg>
