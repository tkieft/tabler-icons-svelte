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
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-live-photo {classes}"
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
    <circle cx="12" cy="12" r="1" />
    <circle cx="12" cy="12" r="5" />
    <line x1="15.9" y1="20.11" x2="15.9" y2="20.12" />
    <line x1="19.04" y1="17.61" x2="19.04" y2="17.62" />
    <line x1="20.77" y1="14" x2="20.77" y2="14.01" />
    <line x1="20.77" y1="10" x2="20.77" y2="10.01" />
    <line x1="19.04" y1="6.39" x2="19.04" y2="6.4" />
    <line x1="15.9" y1="3.89" x2="15.9" y2="3.9" />
    <line x1="12" y1="3" x2="12" y2="3.01" />
    <line x1="8.1" y1="3.89" x2="8.1" y2="3.9" />
    <line x1="4.96" y1="6.39" x2="4.96" y2="6.4" />
    <line x1="3.23" y1="10" x2="3.23" y2="10.01" />
    <line x1="3.23" y1="14" x2="3.23" y2="14.01" />
    <line x1="4.96" y1="17.61" x2="4.96" y2="17.62" />
    <line x1="8.1" y1="20.11" x2="8.1" y2="20.12" />
    <line x1="12" y1="21" x2="12" y2="21.01" />
</svg>
