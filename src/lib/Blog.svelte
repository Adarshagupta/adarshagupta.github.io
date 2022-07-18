<script>
  import monster from "../assets/monster.jpg";
  import svelte from "../assets/svelte.png";
  import svelted from "../assets/svelte.svg";
</script>

<section class="blog">
  <h1>Blogs</h1>
  <a href="">
  <div class="articles">
    <div class="article1">
      <img class="article_img" src={monster} alt="" />
      <div class="texts">
        <h3>Monsters </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
          quidem.
        </p>
      </div>
    </div>
  </div>
</a>
  <div class="articles">
    <div class="article1">
      <img class="article_img" src={svelte} alt="" />
      <div class="texts">
        <h3>Article 1</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
          quidem.
        </p>
      </div>
    </div>
  </div>
  <div class="articles">
    <div class="article1">
      <img class="article_img" src={svelted} alt="" />
      <div class="texts">
        <h3>Article 1</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
          quidem.
        </p>
      </div>
    </div>
  </div>
</section>

<style>

  .articles:hover{
    border-color: #646cff;

  }
  .article1 {
    height: 100px;
    background-color: rgba(94, 92, 92, 0.256);
    padding: 10px;
    text-align: left;
    border-radius: 20px;
    overflow: hidden;
    margin-bottom: 10px;
  }
 a{
  color: aliceblue;
 }
 a:hover{
  color: #000dfb;
 }
  .article_img {
    position: relative;
    width: 100px;
    height: 100%;
    float: left;
    margin-right: 10px;
    border-radius: 20px;
  }
  .texts {
    position: relative;
    margin: 10px;
  }
</style>
