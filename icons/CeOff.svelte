<script>
    export let size = 24;
    export let color = "currentColor";
    export let fill = "none";
    export let strokeWidth = 2;
    export let element = undefined;
    export let icon = true;
    let classes = "";
    export { classes as class };
</script>

<svg
    bind:this="{element}"
    on:click
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-ce-off {classes}"
    width="{size}"
    height="{size}"
    viewBox="0 0 24 24"
    stroke="{color}"
    stroke-width="{strokeWidth}"
    fill="{fill}"
    stroke-linecap="round"
    stroke-linejoin="round"
>
    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
    <path d="M11 4a7.99 7.99 0 0 0 -2.581 .426" />
    <path d="M5.867 5.864a8 8 0 0 0 5.133 14.136" />
    <path d="M20 4a8.001 8.001 0 0 0 -7.29 4.7" />
    <path d="M12 12a8 8 0 0 0 8 8" />
    <path d="M16 12h4" />
    <path d="M3 3l18 18" />
</svg>
