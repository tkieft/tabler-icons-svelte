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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-aperture {classes}"
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
    <circle cx="12" cy="12" r="9" />
    <line x1="3.6" y1="15" x2="14.15" y2="15" />
    <line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(72 12 12)" />
    <line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(144 12 12)" />
    <line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(216 12 12)" />
    <line x1="3.6" y1="15" x2="14.15" y2="15" transform="rotate(288 12 12)" />
</svg>
