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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-gender-genderqueer {classes}"
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
    <circle transform="matrix(1 0 0 -1 0 32)" cx="12" cy="16" r="5" />
    <path d="M12 11v-8" />
    <path d="M14.5 4.5l-5 3" />
    <path d="M9.5 4.5l5 3" />
</svg>
