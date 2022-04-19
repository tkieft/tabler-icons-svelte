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
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-fold-down {classes}"
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
    <path d="M12 11v8l3 -3m-6 0l3 3" />
    <line x1="9" y1="7" x2="10" y2="7" />
    <line x1="14" y1="7" x2="15" y2="7" />
    <line x1="19" y1="7" x2="20" y2="7" />
    <line x1="4" y1="7" x2="5" y2="7" />
</svg>
