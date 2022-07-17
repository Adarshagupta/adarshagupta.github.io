<section class="navbar">
    <div class="menu">
      <ul>
        <li>
          <a href="">Home</a>
        </li>
        <li>
          <a href="">About</a>
        </li>
        <li>
          <a href="">Contact</a>
        </li>
      </ul>
    </div>
  </section>
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