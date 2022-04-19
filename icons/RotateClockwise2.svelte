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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-rotate-clockwise-2 {classes}"
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
    <path d="M9 4.55a8 8 0 0 1 6 14.9m0 -4.45v5h5" />
    <line x1="5.63" y1="7.16" x2="5.63" y2="7.17" />
    <line x1="4.06" y1="11" x2="4.06" y2="11.01" />
    <line x1="4.63" y1="15.1" x2="4.63" y2="15.11" />
    <line x1="7.16" y1="18.37" x2="7.16" y2="18.38" />
    <line x1="11" y1="19.94" x2="11" y2="19.95" />
</svg>
