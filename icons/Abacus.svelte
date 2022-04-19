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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-abacus {classes}"
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
    <path d="M5 3v18" />
    <path d="M19 21v-18" />
    <path d="M5 7h14" />
    <path d="M5 15h14" />
    <path d="M8 13v4" />
    <path d="M11 13v4" />
    <path d="M16 13v4" />
    <path d="M14 5v4" />
    <path d="M11 5v4" />
    <path d="M8 5v4" />
    <path d="M3 21h18" />
</svg>
