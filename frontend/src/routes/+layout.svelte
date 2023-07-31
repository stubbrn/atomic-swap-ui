<script>
  import "../app.postcss";
  import Navbar from "../lib/Navbar.svelte";
  import Sidebar from "../lib/Sidebar.svelte";
  import StatusBar from "../lib/StatusBar.svelte";
</script>
 
<main>
  <div style="display: flex; height:100vh;">
    <Sidebar></Sidebar>
    <div style="margin-left: 150px; width: 100%;">
    <slot />
    </div>
  </div>
</main>

<style>
</style>
