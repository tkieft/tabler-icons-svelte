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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-drone-off {classes}"
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
    <path d="M14 14h-4v-4" />
    <path d="M10 10l-3.5 -3.5" />
    <path
        d="M9.957 5.95a3.503 3.503 0 0 0 -2.917 -2.91m-3.02 .989a3.5 3.5 0 0 0 1.98 5.936"
    />
    <path d="M14 10l3.5 -3.5" />
    <path d="M18 9.965a3.5 3.5 0 1 0 -3.966 -3.965" />
    <line x1="14" y1="14" x2="17.5" y2="17.5" />
    <path
        d="M14.035 18a3.5 3.5 0 0 0 5.936 1.98m.987 -3.026a3.503 3.503 0 0 0 -2.918 -2.913"
    />
    <line x1="10" y1="14" x2="6.5" y2="17.5" />
    <path d="M6 14.035a3.5 3.5 0 1 0 3.966 3.965" />
    <line x1="3" y1="3" x2="21" y2="21" />
</svg>
