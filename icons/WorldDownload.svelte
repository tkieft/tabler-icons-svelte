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
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-world-download {classes}"
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
    <path d="M21 12a9 9 0 1 0 -9 9" />
    <path d="M3.6 9h16.8" />
    <path d="M3.6 15h8.4" />
    <path d="M11.578 3a17 17 0 0 0 0 18" />
    <path d="M12.5 3c1.719 2.755 2.5 5.876 2.5 9" />
    <path d="M18 14v7m-3 -3l3 3l3 -3" />
</svg>
