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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-line-height {classes}"
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
    <polyline points="3 8 6 5 9 8" />
    <polyline points="3 16 6 19 9 16" />
    <line x1="6" y1="5" x2="6" y2="19" />
    <line x1="13" y1="6" x2="20" y2="6" />
    <line x1="13" y1="12" x2="20" y2="12" />
    <line x1="13" y1="18" x2="20" y2="18" />
</svg>
