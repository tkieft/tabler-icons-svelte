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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-circle-dotted {classes}"
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
    <line x1="7.5" y1="4.21" x2="7.5" y2="4.22" />
    <line x1="4.21" y1="7.5" x2="4.21" y2="7.51" />
    <line x1="3" y1="12" x2="3" y2="12.01" />
    <line x1="4.21" y1="16.5" x2="4.21" y2="16.51" />
    <line x1="7.5" y1="19.79" x2="7.5" y2="19.8" />
    <line x1="12" y1="21" x2="12" y2="21.01" />
    <line x1="16.5" y1="19.79" x2="16.5" y2="19.8" />
    <line x1="19.79" y1="16.5" x2="19.79" y2="16.51" />
    <line x1="21" y1="12" x2="21" y2="12.01" />
    <line x1="19.79" y1="7.5" x2="19.79" y2="7.51" />
    <line x1="16.5" y1="4.21" x2="16.5" y2="4.22" />
    <line x1="12" y1="3" x2="12" y2="3.01" />
</svg>
