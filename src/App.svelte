<script>
  import adarsh from "./assets/adarsh.jpg";
  import Counter from "./lib/Counter.svelte";
  import Navbar from "./lib/Navbar.svelte";
  import Knowledge from "./lib/Knowledge.svelte";
  import Main from "./lib/Main.svelte";
  import Projects from "./lib/Projects.svelte";
  import Blog from './lib/Blog.svelte';
</script>

<main>
  <Navbar />
  <Main />
  <Knowledge />
  <Projects />
  <Blog />
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