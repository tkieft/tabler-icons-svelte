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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-emergency-bed {classes}"
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
    <circle cx="16" cy="18" r="2" />
    <circle cx="8" cy="18" r="2" />
    <path d="M4 8l2.1 2.8a3 3 0 0 0 2.4 1.2h11.5" />
    <path d="M10 6h4" />
    <path d="M12 4v4" />
    <path d="M12 12v2l-2.5 2.5" />
    <path d="M14.5 16.5l-2.5 -2.5" />
</svg>
