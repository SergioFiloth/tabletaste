<script>
    let images = [
        {
            alt: "xxx",
            src: "/img/1.jpg",
        },
        {
            alt: "xxx",
            src: "/img/2.jpg",
        },
        {
            alt: "xxx",
            src: "/img/3.jpg",
        },
    ];
</script>

<div class="Gallery-images">
    {#each images as image}
        <div class="Image--card" style="background-image: url('{image.src}')" />
    {/each}
</div>

<style>
    .Gallery-images {
        gap: 2rem;
        display: grid;
        width: 75%;
        margin: 0 auto;
    }
    .Image--card {
        background-size: cover;
        height: 280px;
    }
    @media screen and (min-width: 768px) {
        .Gallery-images {
            width: initial;
            gap: 2rem;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
        }
    }
</style>
