<script >
    import Navbar from "$lib/components/ui/button/Navbar.svelte";
    import Footer from "$lib/components/ui/Footer.svelte";
import "../app.css";
    import {ModeWatcher} from "mode-watcher"
  
   
</script>

<ModeWatcher/>
<Navbar/>
<slot></slot>
<Footer/>
