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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-access-point {classes}"
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
    <line x1="12" y1="12" x2="12" y2="12.01" />
    <path d="M14.828 9.172a4 4 0 0 1 0 5.656" />
    <path d="M17.657 6.343a8 8 0 0 1 0 11.314" />
    <path d="M9.168 14.828a4 4 0 0 1 0 -5.656" />
    <path d="M6.337 17.657a8 8 0 0 1 0 -11.314" />
</svg>
