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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-toilet-paper {classes}"
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
    <ellipse cx="6" cy="10" rx="3" ry="7" />
    <path d="M21 10c0 -3.866 -1.343 -7 -3 -7" />
    <path d="M6 3h12" />
    <path d="M21 10v10l-3 -1l-3 2l-3 -3l-3 2v-10" />
    <path d="M6 10h.01" />
</svg>
