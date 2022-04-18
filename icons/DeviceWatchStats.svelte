<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-tabler icon-tabler-device-watch-stats {classes}"
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
    <rect x="6" y="6" width="12" height="12" rx="3" />
    <path d="M9 18v3h6v-3" />
    <path d="M9 6v-3h6v3" />
    <path d="M9 14v-4" />
    <path d="M12 14v-1" />
    <path d="M15 14v-3" />
</svg>
