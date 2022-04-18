<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-tabler icon-tabler-gender-intergender {classes}"
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
    <path d="M13.5 11.5l6.5 6.5v-4" />
    <path d="M11.5 13.5l6.5 6.5" />
    <circle transform="matrix(1 0 0 -1 0 18)" cx="9" cy="9" r="5" />
    <path d="M14 20l2 -2" />
</svg>
