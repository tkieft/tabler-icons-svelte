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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-adjustments {classes}"
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
    <circle cx="6" cy="10" r="2" />
    <line x1="6" y1="4" x2="6" y2="8" />
    <line x1="6" y1="12" x2="6" y2="20" />
    <circle cx="12" cy="16" r="2" />
    <line x1="12" y1="4" x2="12" y2="14" />
    <line x1="12" y1="18" x2="12" y2="20" />
    <circle cx="18" cy="7" r="2" />
    <line x1="18" y1="4" x2="18" y2="5" />
    <line x1="18" y1="9" x2="18" y2="20" />
</svg>
