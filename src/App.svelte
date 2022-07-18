<script>

  import Navbar from "./lib/Navbar.svelte";
  
  import { Router, Link, Route } from "svelte-routing";
import Home from "./lib/Home.svelte";
import About from "./pages/About.svelte"
export let url = "";
</script>

<main id="app">

  <Navbar />
  <Router url="{url}">
    <nav>
      <Link to="/"></Link>

    </nav>
    <div>
      <Route path="/"><Home /></Route>

    </div>
  </Router>
  

  
  <button>Hire Me!</button>
  <h1>Keep It simple!</h1>

</main>
<style>
  button{
    position: fixed;
    bottom: 20px;
    right: 20px;
  }
  
</style>