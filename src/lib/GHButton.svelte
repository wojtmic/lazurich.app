<script>
    import Icon from "@iconify/svelte";
</script>

<a class="btn center" href="https://github.com/wojtmic/lazurich">
    <Icon icon="simple-icons:github" width="20" />
    GitHub
</a>

<style>
    .btn {
        display: inline-block;
        padding: 0.75rem 1.5rem;
        border: none;
        border-radius: 8px;
        background: #4a7dff;
        color: white;
        font: inherit;
        font-weight: 600;
        text-decoration: none;
        cursor: pointer;
        transition: background 0.15s, transform 0.15s;
    }

    .btn:hover {
        background: #3a6af0;
        transform: translateY(-2px);
    }

    .btn:active {
        transform: translateY(0);
    }
</style>