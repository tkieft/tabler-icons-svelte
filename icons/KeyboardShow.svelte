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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-keyboard-show {classes}"
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
    <rect x="2" y="3" width="20" height="12" rx="2" />
    <line x1="6" y1="7" x2="6" y2="7" />
    <line x1="10" y1="7" x2="10" y2="7" />
    <line x1="14" y1="7" x2="14" y2="7" />
    <line x1="18" y1="7" x2="18" y2="7" />
    <line x1="6" y1="11" x2="6" y2="11.01" />
    <line x1="18" y1="11" x2="18" y2="11.01" />
    <line x1="10" y1="11" x2="14" y2="11" />
    <path d="M10 19l2 2l2 -2" />
</svg>
