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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-battery-automotive {classes}"
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
    <rect x="3" y="6" width="18" height="14" rx="2" />
    <path d="M6 6v-2" />
    <line x1="19" y1="4" x2="19" y2="6" />
    <line x1="6.5" y1="13" x2="9.5" y2="13" />
    <line x1="14.5" y1="13" x2="17.5" y2="13" />
    <line x1="16" y1="11.5" x2="16" y2="14.5" />
</svg>
