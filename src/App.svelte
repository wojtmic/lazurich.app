<script>
    import Logo from "./lib/Logo.svelte";
    import GHButton from "./lib/GHButton.svelte";
</script>

<link rel="icon" type="image/png" href="/favicon.png" />


<div class="hero">
    <Logo />
    <p class="center">the launcher that launches the game</p>
    <p class="center small dim">sometimes</p>
    <p class="center small dim">if you couldn't tell this is a work in progress</p>

    <GHButton />
</div>

<style>
    .center {
        text-align: center;
        margin: 0 0;
    }

    .small {
        font-size: 12px;
    }

    .dim {
        color: #8e8e8f;
    }

    .hero {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 0.25rem;
        padding-top: 5vh;
    }
</style>