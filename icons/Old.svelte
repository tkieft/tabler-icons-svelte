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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-old {classes}"
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
    <path d="M11 21l-1 -4l-2 -3v-6" />
    <path d="M5 14l-1 -3l4 -3l3 2l3 .5" />
    <circle cx="8" cy="4" r="1" />
    <path d="M7 17l-2 4" />
    <path d="M16 21v-8.5a1.5 1.5 0 0 1 3 0v.5" />
</svg>
