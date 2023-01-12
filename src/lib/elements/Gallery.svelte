<script>
    import GalleryImages from "$lib/components/GalleryImages.svelte";
</script>

<div class="Gallery">
    <div class="Gallery--container">
        <h2 class="Gallery__title">Our products gallery</h2>
        <p class="Gallery__text">
            Table Taste will be offering a delicatessen of Italian meats,
            Italian salami, Calabrese salami as well as Prosciutto, seasonal
            fruits, an assortment of cheeses, nuts, crackers with an in-house
            dip and you can enjoy a variety of chocolates that will decorate
            your table with the warmest welcome. All of this accompanied by
            beautiful flower arrangements and all candlelit to assure our guests
            can delight in the art that was inspired by us here at Table Taste.
        </p>
        <GalleryImages />
    </div>
</div>

<style>
    .Gallery {
        padding: 2rem 0 5rem;
        font-weight: 500;
    }
    .Gallery--container {
        width: 80%;
        margin: 0 auto;
        text-align: center;
    }
    .Gallery__title {
        font-size: 1.5rem;
        margin-bottom: 1.75rem;
    }
    .Gallery__text {
        font-size: 1.25rem;
        margin: 0 auto;
        margin-bottom: 1.75rem;
    }
    @media screen and (min-width: 768px) {
        .Gallery__text {
            width: 65%;
        }
    }
</style>
