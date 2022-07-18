<script>
    import grofmart from '../assets/grofmart.png'
    import monster from '../assets/monster.jpg'
    import team from '../assets/team.jpg'
</script>
<section>
    <h1>Future Projects</h1>
    <div class="projects">
            <button class="btn">
                <img src={grofmart} width="200" alt="github" />
                <p><b><a href="https://grofmart.com/">Watch To Earn</a></b>Watch to earn is first ever Blockchain project where anyone can earn currency watching videos</p>
            </button>
            <button class="btn">
                <img src={monster} width="80" class="monster" alt="monster" />
                <p><b><a>Move to Earn</a></b> is NFT and blockchain project on solana network with other metaverse projects.</p>
            </button>
            <button class="btn">
                <img src={team} width="80" class="monster" alt="monster" />
                <p><b><a href="https://Penpot.com">Monsters Metaverse</a></b> is an open-source designing project for teams. Buid with latest high-lever technology.</p>
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