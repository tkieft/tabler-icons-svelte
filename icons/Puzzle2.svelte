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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-puzzle-2 {classes}"
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
    <rect x="4" y="4" width="16" height="16" rx="2" />
    <path
        d="M12 4v2.5a0.5 .5 0 0 1 -.5 .5a1.5 1.5 0 0 0 0 3a0.5 .5 0 0 1 .5 .5v1.5"
    />
    <path
        d="M12 12v1.5a0.5 .5 0 0 0 .5 .5a1.5 1.5 0 0 1 0 3a0.5 .5 0 0 0 -.5 .5v2.5"
    />
    <path
        d="M20 12h-2.5a0.5 .5 0 0 1 -.5 -.5a1.5 1.5 0 0 0 -3 0a0.5 .5 0 0 1 -.5 .5h-1.5"
    />
    <path
        d="M12 12h-1.5a0.5 .5 0 0 0 -.5 .5a1.5 1.5 0 0 1 -3 0a0.5 .5 0 0 0 -.5 -.5h-2.5"
    />
</svg>
