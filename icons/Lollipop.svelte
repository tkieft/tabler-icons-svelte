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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-lollipop {classes}"
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
    <circle cx="14" cy="10" r="7" />
    <path d="M21 10a3.5 3.5 0 0 0 -7 0" />
    <path d="M14 10a3.5 3.5 0 0 1 -7 0" />
    <path d="M14 17a3.5 3.5 0 0 0 0 -7" />
    <path d="M14 3a3.5 3.5 0 0 0 0 7" />
    <path d="M3 21l6 -6" />
</svg>
