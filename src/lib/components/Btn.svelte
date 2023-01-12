<script>
    export let href = "#",
        text = "Btn",
        backgroundColor = "#232930",
        colorText = "#fff",
        target = "";
</script>

<a
    class="Btn"
    {href}
    {target}
    style="background-color: {backgroundColor}; color: {colorText}">{text}</a
>

<style>
    .Btn {
        display: inline-block;
        padding: 1rem 2rem;
        text-decoration: none;
        font-weight: bold;
        border-radius: 2px;
        transition: all 0.3s;
    }
    @media (hover: hover) {
        .Btn:hover {
            transform: scale(1.01);
            box-shadow: 0 0 5px 3px #ccc;
        }
    }
</style>
