<script>
    import Btn from "$lib/components/Btn.svelte";
</script>

<div class="Menu">
    <div class="Menu--container">
        <div class="Menu--open-link">
            <div class="Menu--title">
                <h3 class="Menu--open-link__title">See Our Menu</h3>
            </div>
            <Btn
                text="Open Menu"
                href="/documents/menu_table_taste.pdf"
                backgroundColor="#232930"
                colorText="#fff"
                target="_blanck"
            />
        </div>
    </div>
</div>

<style>
    .Menu {
        padding: 2rem 0;
    }
    .Menu--container {
        width: 80%;
        margin: 0 auto;
        display: grid;
        text-align: center;
        gap: 2rem;
    }
    .Menu--open-link {
        display: flex;
        gap: 2rem;
        justify-content: center;
        align-items: center;
    }
    .Menu--title {
        height: 100%;
        display: flex;
        align-items: center;
    }
    .Menu--open-link__title {
        font-size: 1.75rem;
    }
    @media screen and (min-width: 768px) {
        .Menu--container {
            width: 80%;
            margin: 0 auto;
            display: grid;
            gap: 0;
            text-align: initial;
        }
    }
</style>
