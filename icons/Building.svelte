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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-building {classes}"
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
    <line x1="9" y1="8" x2="10" y2="8" />
    <line x1="9" y1="12" x2="10" y2="12" />
    <line x1="9" y1="16" x2="10" y2="16" />
    <line x1="14" y1="8" x2="15" y2="8" />
    <line x1="14" y1="12" x2="15" y2="12" />
    <line x1="14" y1="16" x2="15" y2="16" />
    <path d="M5 21v-16a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16" />
</svg>
