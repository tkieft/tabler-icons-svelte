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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-atom {classes}"
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
    <line x1="12" y1="12" x2="12" y2="12.01" />
    <path
        d="M12 2a4 10 0 0 0 -4 10a4 10 0 0 0 4 10a4 10 0 0 0 4 -10a4 10 0 0 0 -4 -10"
        transform="rotate(45 12 12)"
    />
    <path
        d="M12 2a4 10 0 0 0 -4 10a4 10 0 0 0 4 10a4 10 0 0 0 4 -10a4 10 0 0 0 -4 -10"
        transform="rotate(-45 12 12)"
    />
</svg>
