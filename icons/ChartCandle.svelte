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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-chart-candle {classes}"
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
    <rect x="4" y="6" width="4" height="5" rx="1" />
    <line x1="6" y1="4" x2="6" y2="6" />
    <line x1="6" y1="11" x2="6" y2="20" />
    <rect x="10" y="14" width="4" height="5" rx="1" />
    <line x1="12" y1="4" x2="12" y2="14" />
    <line x1="12" y1="19" x2="12" y2="20" />
    <rect x="16" y="5" width="4" height="6" rx="1" />
    <line x1="18" y1="4" x2="18" y2="5" />
    <line x1="18" y1="11" x2="18" y2="20" />
</svg>
