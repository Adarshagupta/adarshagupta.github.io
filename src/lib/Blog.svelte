<script>
  import monster from "../assets/monster.jpg";
</script>

<section class="blog">
  <h1>Blogs</h1>
  <div class="articles">
    <div class="article1">
      <img class="article_img" src={monster} alt="" />
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
  .article1 {
    width: 100%;
    height: 100px;
    background-color: rgba(94, 92, 92, 0.256);
    padding: 10px;
    text-align: left;
    border-radius: 20px;
    overflow: hidden;
  }
  .article_img {
    position: relative;
    width: 100px;
    height: 100%;
    float: left;
    margin-right: 10px;
  }
  .texts {
    position: relative;
    margin: 10px;
  }
</style>
