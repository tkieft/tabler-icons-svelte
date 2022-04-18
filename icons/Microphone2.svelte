<script>
    export let size = 24;
    export let color = "currentColor";
    export let strokeWidth = 2;
    export let icon = true;
    let classes = "";
    export { classes as class };
</script>

<svg
    xmlns="http://www.w3.org/2000/svg"
    class="{icon ? 'icon' : ''} icon-tabler icon-tabler-microphone-2 {classes}"
    width="{size}"
    height="{size}"
    viewBox="0 0 24 24"
    stroke="{color}"
    stroke-width="{strokeWidth}"
    fill="none"
    stroke-linecap="round"
    stroke-linejoin="round"
>
    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
    <path d="M15.002 12.9a5 5 0 1 0 -3.902 -3.9" />
    <path
        d="M15.002 12.9l-3.902 -3.899l-7.513 8.584a2 2 0 1 0 2.827 2.83l8.588 -7.515z"
    />
</svg>
