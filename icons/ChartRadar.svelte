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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-chart-radar {classes}"
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
    <path d="M12 3l9.5 7l-3.5 11h-12l-3.5 -11z" />
    <path d="M12 7.5l5.5 4l-2.5 5.5h-6.5l-2 -5.5z" />
    <path d="M2.5 10l9.5 3l9.5 -3" />
    <path d="M12 3v10l6 8" />
    <path d="M6 21l6 -8" />
</svg>
