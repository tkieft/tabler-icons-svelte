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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-brightness-down {classes}"
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
    <circle cx="12" cy="12" r="3" />
    <line x1="12" y1="5" x2="12" y2="5.01" />
    <line x1="17" y1="7" x2="17" y2="7.01" />
    <line x1="19" y1="12" x2="19" y2="12.01" />
    <line x1="17" y1="17" x2="17" y2="17.01" />
    <line x1="12" y1="19" x2="12" y2="19.01" />
    <line x1="7" y1="17" x2="7" y2="17.01" />
    <line x1="5" y1="12" x2="5" y2="12.01" />
    <line x1="7" y1="7" x2="7" y2="7.01" />
</svg>
