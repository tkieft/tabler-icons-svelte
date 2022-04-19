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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-tools-kitchen {classes}"
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
    <path d="M4 3h8l-1 9h-6z" />
    <path d="M7 18h2v3h-2z" />
    <path d="M20 3v12h-5c-.023 -3.681 .184 -7.406 5 -12z" />
    <path d="M20 15v6h-1v-3" />
    <line x1="8" y1="12" x2="8" y2="18" />
</svg>
