<script >
    import Navbar from "$lib/components/ui/button/Navbar.svelte";
import "../app.css";
    import {ModeWatcher} from "mode-watcher"
    
   
</script>

<ModeWatcher/>
<Navbar/>
<slot></slot>
