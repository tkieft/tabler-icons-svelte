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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-atom-2 {classes}"
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
    <circle cx="12" cy="12" r="3" />
    <line x1="12" y1="21" x2="12" y2="21.01" />
    <line x1="3" y1="9" x2="3" y2="9.01" />
    <line x1="21" y1="9" x2="21" y2="9.01" />
    <path d="M8 20.1a9 9 0 0 1 -5 -7.1" />
    <path d="M16 20.1a9 9 0 0 0 5 -7.1" />
    <path d="M6.2 5a9 9 0 0 1 11.4 0" />
</svg>
