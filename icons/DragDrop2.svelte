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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-drag-drop-2 {classes}"
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
    <rect x="8" y="8" width="12" height="12" rx="2" />
    <line x1="4" y1="4" x2="4" y2="4.01" />
    <line x1="8" y1="4" x2="8" y2="4.01" />
    <line x1="12" y1="4" x2="12" y2="4.01" />
    <line x1="16" y1="4" x2="16" y2="4.01" />
    <line x1="4" y1="8" x2="4" y2="8.01" />
    <line x1="4" y1="12" x2="4" y2="12.01" />
    <line x1="4" y1="16" x2="4" y2="16.01" />
</svg>
