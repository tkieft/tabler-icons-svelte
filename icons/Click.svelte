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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-click {classes}"
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
    <line x1="3" y1="12" x2="6" y2="12" />
    <line x1="12" y1="3" x2="12" y2="6" />
    <line x1="7.8" y1="7.8" x2="5.6" y2="5.6" />
    <line x1="16.2" y1="7.8" x2="18.4" y2="5.6" />
    <line x1="7.8" y1="16.2" x2="5.6" y2="18.4" />
    <path d="M12 12l9 3l-4 2l-2 4l-3 -9" />
</svg>
