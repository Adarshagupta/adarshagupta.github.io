<script>
import grofmart from "../assets/grofmart.png";
import monster from "../assets/monster.jpg";
import team from "../assets/team.jpg";
</script>
<section>
    <h1>Live Projects</h1>
    <p>These are all project I am working on</p>
    <div>
        <button class="btn">
            <img src={grofmart} width="200" alt="github" />
            <p><b><a href="https://grofmart.com/">Grofmart</a></b> is from Nepal's E-Commerce platform launched as BETA Version. </p>
        </button>
        <button class="btn">
            <img src={monster} width="80" class="monster" alt="monster" />
            <p><b><a>Monster City</a></b> is NFT and blockchain project on solana network with other metaverse projects.</p>
        </button>
        <button class="btn">
            <img src={team} width="80" class="monster" alt="monster" />
            <p><b><a href="https://Penpot.com">Team Design</a></b> is an open-source designing project for teams. Buid with latest high-lever technology.</p>
        </button>


    </div>
</section>
<style>
    section{
        margin-top: 50px;
    }
    .btn{
        width: 250px;
        height: 200px;
        border-radius: 20px;
        border: 1px solid white;
        margin: 10px;
        background-color: rgba(0, 8, 69, 0.256);
        display: inline-block;
        overflow: hidden;
        text-decoration: none;
        box-shadow: 3px 3px 4px 2px #0ff;

    }
    .btn:hover{
        filter: drop-shadow(0 0 2em #646cff);

    }
    @media (max-width: 768px) {
        .btn{
            width: 320px;
            height: 320px;
        }
    }
    .monster{
        border-radius: 50%;
    }
</style>