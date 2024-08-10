<script >
    import Navbar from "$lib/components/ui/button/Navbar.svelte";
    import "../app.css";
    import {ModeWatcher} from "mode-watcher"
   import Footer from "$lib/components/ui/Footer.svelte";
</script>

<ModeWatcher/>
<Navbar/>

<main class="min-h-[calc(100dvh-9.5rem)]">
    <slot />
</main>
<!-- <Footer /> -->

