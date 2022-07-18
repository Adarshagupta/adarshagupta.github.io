<script>
  import { Router, Link, Route } from "svelte-routing";
  import About from "../pages/About.svelte";
  export let url = "";
</script>

<div class="navbar">
  <Router {url}>
    <nav>
      <Link to="/">Home</Link>
      <Link to="about">About</Link>
    </nav>
    <div>
      <Route path="about" component={About}></Route>
    </div>
  </Router>
</div>

<style>
  .navbar {
    position: fixed;
    background-color: rgba(2, 0, 48, 0.299);
    color: white;
    top: 0;
    left: 0;
    right: 0;
    margin: 20px;
    padding: -10px;
    z-index: 1;
    border-radius: 20px;
    border: white solid 1px;
  }
  @media (max-width: 768px) {
    .navbar {
      position: fixed;
      background-color: rgba(84, 53, 53, 0.299);
      color: white;
      top: 0;
      left: 0;
      right: 0;
      margin: 20px;
      z-index: 1;
      border-radius: 20px;
      border: white solid 1px;
      max-width: 100%;
    }
  }
  ul {
    display: inline-block;
    text-decoration: none;
  }
  li {
    display: inline-block;
  }
</style>
