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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-git-branch {classes}"
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
    <circle cx="7" cy="18" r="2" />
    <circle cx="7" cy="6" r="2" />
    <circle cx="17" cy="6" r="2" />
    <line x1="7" y1="8" x2="7" y2="16" />
    <path d="M9 18h6a2 2 0 0 0 2 -2v-5" />
    <polyline points="14 14 17 11 20 14" />
</svg>
