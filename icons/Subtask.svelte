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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-subtask {classes}"
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
    <line x1="6" y1="9" x2="12" y2="9" />
    <line x1="4" y1="5" x2="8" y2="5" />
    <path d="M6 5v11a1 1 0 0 0 1 1h5" />
    <rect x="12" y="7" width="8" height="4" rx="1" />
    <rect x="12" y="15" width="8" height="4" rx="1" />
</svg>
