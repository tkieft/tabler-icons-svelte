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
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-ball-volleyball {classes}"
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
    <circle cx="12" cy="12" r="9" />
    <path d="M12 12a8 8 0 0 0 8 4m-12.5 -2.5a12 12 0 0 0 8.5 6.5" />
    <path
        d="M12 12a8 8 0 0 0 8 4m-12.5 -2.5a12 12 0 0 0 8.5 6.5"
        transform="rotate(120 12 12)"
    />
    <path
        d="M12 12a8 8 0 0 0 8 4m-12.5 -2.5a12 12 0 0 0 8.5 6.5"
        transform="rotate(240 12 12)"
    />
</svg>
