<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    export let element = undefined;
    export let icon = true;
    let classes = "";
    export { classes as class };
</script>

<svg
    bind:this="{element}"
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-gender-genderfluid {classes}"
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
    <g transform="rotate(30 -2.778 22.523)">
        <circle cx="4.759" cy="6.021" r="4" />
        <path d="M8.758 6.02v-6" />
        <path d="M.758 12.02v-6" />
    </g>
    <path d="M12 12h.01" />
    <path d="M9 9l-6 -6" />
    <path d="M5.5 8.5l3 -3" />
    <path d="M21 21l-6 -6" />
    <path d="M17 20l3 -3" />
    <path d="M3 7v-4h4" />
</svg>
