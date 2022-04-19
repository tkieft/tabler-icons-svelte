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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-beer {classes}"
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
    <path
        d="M9 20h6v-4.111a8 8 0 0 1 .845 -3.578l.31 -.622a8 8 0 0 0 .845 -3.578v-4.111h-10v4.111a8 8 0 0 0 .845 3.578l.31 .622a8 8 0 0 1 .845 3.578v4.111z"
    />
    <path d="M7 8h10" />
</svg>
