<script>
    import node from "../assets/node.png";
    import svelte from "../assets/svelte.png";
    import next from "../assets/next.png";
    import bun from "../assets/bun.png";
    import solana from "../assets/solana.png";
    import penpot from "../assets/penpot.jpg";
</script>
<h1>Knowledge Of</h1>
<div class="logo_section">
    <img src={node} alt="node" />
    <img class="svelte" src={svelte} alt="svelte" />
    <img class="svelte" src={next} alt="next" />
    <img class="svelte" src={bun} alt="bun" />
    <img class="svelte" src={solana} alt="solana" />
    <img class="svelte" src={penpot} alt="penport" />

</div>
<style>
    h1{
        margin-top: 50px;
        justify-content: center;align-items: center;
    }
    .logo_section{
        background-color: rgba(0, 8, 69, 0.256);
        height: 50px;
        border-radius: 20px;
        border: 1px solid white;
    }
    img{
        width: 40px;
        height: 40px;
        margin: 5px;
    }
    .svelte{
        border-radius: 50%;
    }
</style>