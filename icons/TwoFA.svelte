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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-2fa {classes}"
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
    <path d="M7 16h-4l3.47 -4.66a2 2 0 1 0 -3.47 -1.54" />
    <path d="M10 16v-8h4" />
    <line x1="10" y1="12" x2="13" y2="12" />
    <path d="M17 16v-6a2 2 0 0 1 4 0v6" />
    <line x1="17" y1="13" x2="21" y2="13" />
</svg>
