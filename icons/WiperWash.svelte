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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-wiper-wash {classes}"
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
    <circle cx="12" cy="20" r="1" />
    <path d="M3 11l5.5 5.5a5 5 0 0 1 7 0l5.5 -5.5a12 12 0 0 0 -18 0" />
    <line x1="12" y1="20" x2="12" y2="6" />
    <path d="M4 6a4 4 0 0 1 .4 -1.8" />
    <path d="M7 2.1a4 4 0 0 1 2 0" />
    <path d="M12 6a4 4 0 0 0 -.4 -1.8" />
    <path d="M12 6a4 4 0 0 1 .4 -1.8" />
    <path d="M15 2.1a4 4 0 0 1 2 0" />
    <path d="M20 6a4 4 0 0 0 -.4 -1.8" />
</svg>
