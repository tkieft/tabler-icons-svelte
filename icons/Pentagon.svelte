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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-pentagon {classes}"
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
        d="M13.2 3.394l7.033 5.237a2 2 0 0 1 .7 2.247l-2.973 8.764a2 2 0 0 1 -1.894 1.358h-8.12a2 2 0 0 1 -1.9 -1.373l-2.896 -8.765a2 2 0 0 1 .696 -2.225l6.958 -5.237a2 2 0 0 1 2.397 -.006z"
    />
</svg>
