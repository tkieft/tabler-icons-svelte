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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-file-settings {classes}"
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
    <circle cx="12" cy="14" r="2" />
    <path d="M12 10.5v1.5" />
    <path d="M12 16v1.5" />
    <path d="M15.031 12.25l-1.299 .75" />
    <path d="M10.268 15l-1.3 .75" />
    <path d="M15 15.803l-1.285 -.773" />
    <path d="M10.285 12.97l-1.285 -.773" />
    <path d="M14 3v4a1 1 0 0 0 1 1h4" />
    <path
        d="M17 21h-10a2 2 0 0 1 -2 -2v-14a2 2 0 0 1 2 -2h7l5 5v11a2 2 0 0 1 -2 2z"
    />
</svg>
