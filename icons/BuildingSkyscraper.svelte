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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-building-skyscraper {classes}"
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
    <line x1="3" y1="21" x2="21" y2="21" />
    <path d="M5 21v-14l8 -4v18" />
    <path d="M19 21v-10l-6 -4" />
    <line x1="9" y1="9" x2="9" y2="9.01" />
    <line x1="9" y1="12" x2="9" y2="12.01" />
    <line x1="9" y1="15" x2="9" y2="15.01" />
    <line x1="9" y1="18" x2="9" y2="18.01" />
</svg>
