<script>
    import "../app.css";
    import NavBar from "../components/NavBar.svelte";
    import "@fontsource/zen-dots";
</script>


<div class="h-screen overflow-y-hidden">
    <NavBar />
    <slot />
</div>