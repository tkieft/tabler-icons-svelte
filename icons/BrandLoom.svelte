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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-brand-loom {classes}"
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
    <path d="M17.464 6.518a6.001 6.001 0 1 0 -3.023 7.965" />
    <path d="M17.482 17.464a6.001 6.001 0 1 0 -7.965 -3.023" />
    <path d="M6.54 17.482a6.001 6.001 0 1 0 3.024 -7.965" />
    <path d="M6.518 6.54a6.001 6.001 0 1 0 7.965 3.024" />
</svg>
