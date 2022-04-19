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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-plant-2 {classes}"
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
    <path d="M2 9a10 10 0 1 0 20 0" />
    <path d="M12 19a10 10 0 0 1 10 -10" />
    <path d="M2 9a10 10 0 0 1 10 10" />
    <path d="M12 4a9.7 9.7 0 0 1 2.99 7.5" />
    <path d="M9.01 11.5a9.7 9.7 0 0 1 2.99 -7.5" />
</svg>
