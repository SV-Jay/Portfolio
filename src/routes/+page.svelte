<h1>Sv Jay's Portfolio</h1>
<a class="red_link" href="/about">About me Page</a>
<a class="red_link" href="/achievements">Achievements</a>

<script>
     import CoolButton from "../lib/CoolButton.svelte";
</script>

<CoolButton></CoolButton>

<style>
    h1 {
        color: aqua;
        text-align: center;
    }

    a.red_link {
        color: red;
        padding-left: 3em;       
    }

    :global(body) {
        font-family: cursive; 
        font-size: 20pt;
        background-color: black;
    }
</style>