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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-brand-yahoo {classes}"
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
    <line x1="3" y1="6" x2="8" y2="6" />
    <line x1="7" y1="18" x2="14" y2="18" />
    <path d="M4.5 6l5.5 7v5" />
    <path d="M10 13l6 -5" />
    <line x1="12.5" y1="8" x2="17.5" y2="8" />
    <line x1="20" y1="11" x2="20" y2="15" />
    <line x1="20" y1="18" x2="20" y2="18.01" />
</svg>
