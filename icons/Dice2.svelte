<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="icon icon-tabler icon-tabler-dice-2 {classes}"
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
    <rect x="4" y="4" width="16" height="16" rx="2" />
    <circle cx="9.5" cy="9.5" r=".5" fill="currentColor" />
    <circle cx="14.5" cy="14.5" r=".5" fill="currentColor" />
</svg>
