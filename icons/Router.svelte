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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-router {classes}"
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
    <rect x="3" y="13" width="18" height="8" rx="2" />
    <line x1="17" y1="17" x2="17" y2="17.01" />
    <line x1="13" y1="17" x2="13" y2="17.01" />
    <line x1="15" y1="13" x2="15" y2="11" />
    <path d="M11.75 8.75a4 4 0 0 1 6.5 0" />
    <path d="M8.5 6.5a8 8 0 0 1 13 0" />
</svg>
