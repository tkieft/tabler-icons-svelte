<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-tabler icon-tabler-fountain {classes}"
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
    <path d="M9 16v-5a2 2 0 1 0 -4 0" />
    <path d="M15 16v-5a2 2 0 1 1 4 0" />
    <path d="M12 16v-10a3 3 0 0 1 6 0" />
    <path d="M6 6a3 3 0 0 1 6 0" />
    <path d="M3 16h18v2a3 3 0 0 1 -3 3h-12a3 3 0 0 1 -3 -3v-2z" />
</svg>
