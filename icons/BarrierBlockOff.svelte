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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-barrier-block-off {classes}"
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
    <path d="M11 7h8a1 1 0 0 1 1 1v7c0 .27 -.107 .516 -.282 .696" />
    <path d="M16 16h-11a1 1 0 0 1 -1 -1v-7a1 1 0 0 1 1 -1h2" />
    <path d="M7 16v4" />
    <path d="M7.5 16l4.244 -4.244" />
    <path d="M13.745 9.755l2.755 -2.755" />
    <path d="M13.5 16l1.249 -1.249" />
    <path d="M16.741 12.759l3.259 -3.259" />
    <path d="M4 13.5l4.752 -4.752" />
    <path d="M17 17v3" />
    <path d="M5 20h4" />
    <path d="M15 20h4" />
    <path d="M17 7v-2" />
    <path d="M3 3l18 18" />
</svg>
