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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-triangles {classes}"
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
        d="M9.974 21h8.052a0.975 .975 0 0 0 .81 -1.517l-4.025 -6.048a0.973 .973 0 0 0 -1.622 0l-4.025 6.048a0.977 .977 0 0 0 .81 1.517z"
    />
    <path
        d="M4.98 16h14.04c.542 0 .98 -.443 .98 -.989a0.995 .995 0 0 0 -.156 -.534l-7.02 -11.023a0.974 .974 0 0 0 -1.648 0l-7.02 11.023a0.994 .994 0 0 0 .294 1.366a0.973 .973 0 0 0 .53 .157z"
    />
</svg>
