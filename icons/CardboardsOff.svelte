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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-cardboards-off {classes}"
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
        d="M20.96 16.953c.026 -.147 .04 -.298 .04 -.453v-8.5a2 2 0 0 0 -2 -2h-9m-4 0h-1a2 2 0 0 0 -2 2v8.5a2.5 2.5 0 0 0 2.5 2.5h1.06a3 3 0 0 0 2.34 -1.13l1.54 -1.92a2 2 0 0 1 3.12 0l1.54 1.92a3 3 0 0 0 2.34 1.13h1.06c.155 0 .307 -.014 .454 -.041"
    />
    <circle cx="8" cy="12" r="1" />
    <path d="M16.714 12.7a1 1 0 0 0 -1.417 -1.411l1.417 1.41z" />
    <path d="M3 3l18 18" />
</svg>
