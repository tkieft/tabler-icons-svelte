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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-drone {classes}"
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
    <path d="M10 10h4v4h-4z" />
    <line x1="10" y1="10" x2="6.5" y2="6.5" />
    <path d="M9.96 6a3.5 3.5 0 1 0 -3.96 3.96" />
    <path d="M14 10l3.5 -3.5" />
    <path d="M18 9.96a3.5 3.5 0 1 0 -3.96 -3.96" />
    <line x1="14" y1="14" x2="17.5" y2="17.5" />
    <path d="M14.04 18a3.5 3.5 0 1 0 3.96 -3.96" />
    <line x1="10" y1="14" x2="6.5" y2="17.5" />
    <path d="M6 14.04a3.5 3.5 0 1 0 3.96 3.96" />
</svg>
