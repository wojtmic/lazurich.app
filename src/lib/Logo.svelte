<script>
    import logo from '../assets/logo.png';
    let {size = 128} = $props();
</script>

<img src={logo} alt="Lazurich Logo" width={size} height={size} class="logo" />

<style>
    .logo {
        display: block;
        margin: 0 auto;
    }
</style>