<script>
    import Sidebar from "../components/sidebar.svelte";
</script>

<slot />
<Sidebar />

<style lang="scss">
    @import "../variable.scss";

    :global(body) {
        margin: 0;
        padding: 0;
        font-family: "Inter", sans-serif;
        background-color: $background;
        overflow-y: hidden;
    }
</style>
