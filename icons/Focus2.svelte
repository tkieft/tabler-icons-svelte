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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-focus-2 {classes}"
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
    <circle cx="12" cy="12" r=".5" fill="currentColor" />
    <circle cx="12" cy="12" r="7" />
    <line x1="12" y1="3" x2="12" y2="5" />
    <line x1="3" y1="12" x2="5" y2="12" />
    <line x1="12" y1="19" x2="12" y2="21" />
    <line x1="19" y1="12" x2="21" y2="12" />
</svg>
