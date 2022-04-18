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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-at-off {classes}"
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
    <path d="M9.174 9.17a4 4 0 0 0 5.646 5.668m1.18 -2.838a4 4 0 0 0 -4 -4" />
    <path
        d="M19.695 15.697a2.5 2.5 0 0 0 1.305 -2.197v-1.5a9 9 0 0 0 -13.055 -8.047m-2.322 1.683a9 9 0 0 0 9.877 14.644"
    />
    <path d="M3 3l18 18" />
</svg>
