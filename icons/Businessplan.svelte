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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-businessplan {classes}"
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
    <ellipse cx="16" cy="6" rx="5" ry="3" />
    <path d="M11 6v4c0 1.657 2.239 3 5 3s5 -1.343 5 -3v-4" />
    <path d="M11 10v4c0 1.657 2.239 3 5 3s5 -1.343 5 -3v-4" />
    <path d="M11 14v4c0 1.657 2.239 3 5 3s5 -1.343 5 -3v-4" />
    <path d="M7 9h-2.5a1.5 1.5 0 0 0 0 3h1a1.5 1.5 0 0 1 0 3h-2.5" />
    <path d="M5 15v1m0 -8v1" />
</svg>
