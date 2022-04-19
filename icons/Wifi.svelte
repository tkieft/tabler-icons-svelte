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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-wifi {classes}"
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
    <line x1="12" y1="18" x2="12.01" y2="18" />
    <path d="M9.172 15.172a4 4 0 0 1 5.656 0" />
    <path d="M6.343 12.343a8 8 0 0 1 11.314 0" />
    <path d="M3.515 9.515c4.686 -4.687 12.284 -4.687 17 0" />
</svg>
