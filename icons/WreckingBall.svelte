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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-wrecking-ball {classes}"
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
    <circle cx="19" cy="13" r="2" />
    <circle cx="4" cy="17" r="2" />
    <circle cx="13" cy="17" r="2" />
    <line x1="13" y1="19" x2="4" y2="19" />
    <line x1="4" y1="15" x2="13" y2="15" />
    <path d="M8 12v-5h2a3 3 0 0 1 3 3v5" />
    <path d="M5 15v-2a1 1 0 0 1 1 -1h7" />
    <path d="M19 11v-7l-6 7" />
</svg>
