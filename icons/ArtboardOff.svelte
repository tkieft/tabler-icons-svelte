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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-artboard-off {classes}"
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
    <path d="M12 8h3a1 1 0 0 1 1 1v3" />
    <path
        d="M15.716 15.698a0.997 .997 0 0 1 -.716 .302h-6a1 1 0 0 1 -1 -1v-6c0 -.273 .11 -.52 .287 -.7"
    />
    <path d="M3 8h1" />
    <path d="M3 16h1" />
    <path d="M8 3v1" />
    <path d="M16 3v1" />
    <path d="M20 8h1" />
    <path d="M20 16h1" />
    <path d="M8 20v1" />
    <path d="M16 20v1" />
    <path d="M3 3l18 18" />
</svg>
