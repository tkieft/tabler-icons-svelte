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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-packge-import {classes}"
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
    <path d="M12 21l-8 -4.5v-9l8 -4.5l8 4.5v4.5" />
    <path d="M12 12l8 -4.5" />
    <path d="M12 12v9" />
    <path d="M12 12l-8 -4.5" />
    <path d="M22 18h-7" />
    <path d="M18 15l-3 3l3 3" />
</svg>
