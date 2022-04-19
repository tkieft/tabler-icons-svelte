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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-fold-up {classes}"
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
    <path d="M12 13v-8l-3 3m6 0l-3 -3" />
    <line x1="9" y1="17" x2="10" y2="17" />
    <line x1="14" y1="17" x2="15" y2="17" />
    <line x1="19" y1="17" x2="20" y2="17" />
    <line x1="4" y1="17" x2="5" y2="17" />
</svg>
