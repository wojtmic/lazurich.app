<script>
    import revi from '../assets/revi.png';
    let {size = 128} = $props();
</script>

<img src={revi} alt="Revi" width={size} height={size} class="flip" />

<style>
    .flip {
        animation: flip 2s ease-in-out infinite;
    }

    @keyframes flip {
        0%, 100% { transform: scaleY(1); }
        50%      { transform: scaleY(-1); }
    }

    @media (prefers-reduced-motion: reduce) {
        .flip { animation: none; }
    }
</style>