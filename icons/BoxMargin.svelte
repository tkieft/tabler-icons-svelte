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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-box-margin {classes}"
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
    <path d="M8 8h8v8h-8z" />
    <path d="M4 4v.01" />
    <path d="M8 4v.01" />
    <path d="M12 4v.01" />
    <path d="M16 4v.01" />
    <path d="M20 4v.01" />
    <path d="M4 20v.01" />
    <path d="M8 20v.01" />
    <path d="M12 20v.01" />
    <path d="M16 20v.01" />
    <path d="M20 20v.01" />
    <path d="M20 16v.01" />
    <path d="M20 12v.01" />
    <path d="M20 8v.01" />
    <path d="M4 16v.01" />
    <path d="M4 12v.01" />
    <path d="M4 8v.01" />
</svg>
