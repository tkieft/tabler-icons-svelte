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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-float-left {classes}"
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
    <rect width="6" height="6" x="4" y="5" rx="1" />
    <line x1="14" y1="7" x2="20" y2="7" />
    <line x1="14" y1="11" x2="20" y2="11" />
    <line x1="4" y1="15" x2="20" y2="15" />
    <line x1="4" y1="19" x2="20" y2="19" />
</svg>
