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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-user-search {classes}"
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
    <circle cx="12" cy="7" r="4" />
    <path d="M6 21v-2a4 4 0 0 1 4 -4h1" />
    <circle cx="16.5" cy="17.5" r="2.5" />
    <path d="M18.5 19.5l2.5 2.5" />
</svg>
