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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-vector-bezier {classes}"
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
    <rect x="3" y="14" width="4" height="4" rx="1" />
    <rect x="17" y="14" width="4" height="4" rx="1" />
    <rect x="10" y="6" width="4" height="4" rx="1" />
    <path d="M10 8.5a6 6 0 0 0 -5 5.5" />
    <path d="M14 8.5a6 6 0 0 1 5 5.5" />
    <line x1="10" y1="8" x2="4" y2="8" />
    <line x1="20" y1="8" x2="14" y2="8" />
    <circle cx="3" cy="8" r="1" />
    <circle cx="21" cy="8" r="1" />
</svg>
