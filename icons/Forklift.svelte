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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-forklift {classes}"
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
    <circle cx="5" cy="17" r="2" />
    <circle cx="14" cy="17" r="2" />
    <line x1="7" y1="17" x2="12" y2="17" />
    <path d="M3 17v-6h13v6" />
    <path d="M5 11v-4h4" />
    <path d="M9 11v-6h4l3 6" />
    <path d="M22 15h-3v-10" />
    <line x1="16" y1="13" x2="19" y2="13" />
</svg>
