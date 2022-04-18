<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-tabler icon-tabler-cone-2 {classes}"
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
    <ellipse cx="12" cy="7" rx="7" ry="3" />
    <path d="M19 7v.5l-7 12.5l-7 -12.5v-.5" />
</svg>
