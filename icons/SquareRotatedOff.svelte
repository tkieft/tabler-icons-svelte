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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-square-rotated-off {classes}"
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
    <path
        d="M16.964 16.952l-3.462 3.461c-.782 .783 -2.222 .783 -3.004 0l-6.911 -6.91c-.783 -.783 -.783 -2.223 0 -3.005l3.455 -3.456m2.003 -2.003l1.453 -1.452c.782 -.783 2.222 -.783 3.004 0l6.911 6.91c.783 .783 .783 2.223 0 3.005l-1.448 1.45"
    />
    <path d="M3 3l18 18" />
</svg>
