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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-biohazard-off {classes}"
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
    <path d="M10.586 10.586a2 2 0 1 0 2.836 2.82" />
    <path
        d="M11.939 14c0 .173 .048 .351 .056 .533v.217a4.75 4.75 0 0 1 -4.533 4.745h-.217"
    />
    <path d="M2.495 14.745a4.75 4.75 0 0 1 7.737 -3.693" />
    <path d="M16.745 19.495a4.75 4.75 0 0 1 -4.69 -5.503h-.06" />
    <path d="M14.533 10.538a4.75 4.75 0 0 1 6.957 3.987v.217" />
    <path
        d="M10.295 10.929a4.75 4.75 0 0 1 -2.988 -3.64m.66 -3.324a4.75 4.75 0 0 1 .5 -.66l.164 -.172"
    />
    <path d="M15.349 3.133a4.75 4.75 0 0 1 -.836 7.385" />
    <path d="M3 3l18 18" />
</svg>
