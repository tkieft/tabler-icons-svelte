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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-sleigh {classes}"
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
    <path d="M3 19h15a4 4 0 0 0 4 -4" />
    <path
        d="M16 15h-9a4 4 0 0 1 -4 -4v-6l1.243 1.243a6 6 0 0 0 4.242 1.757h3.515v2a2 2 0 0 0 2 2h.5a1.5 1.5 0 0 0 1.5 -1.5a1.5 1.5 0 0 1 3 0v1.5a3 3 0 0 1 -3 3z"
    />
    <path d="M15 15v4" />
    <path d="M7 15v4" />
</svg>
