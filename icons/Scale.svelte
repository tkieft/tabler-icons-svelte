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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-scale {classes}"
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
    <line x1="7" y1="20" x2="17" y2="20" />
    <path d="M6 6l6 -1l6 1" />
    <line x1="12" y1="3" x2="12" y2="20" />
    <path d="M9 12l-3 -6l-3 6a3 3 0 0 0 6 0" />
    <path d="M21 12l-3 -6l-3 6a3 3 0 0 0 6 0" />
</svg>
