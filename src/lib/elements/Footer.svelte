<script>
    import Facebook from "$lib/svg/icons/Facebook.svelte";
    import Instagram from "$lib/svg/icons/Instagram.svelte";
</script>

<footer class="Footer">
    <div class="Footer--container">
        <div class="Footer--info">
            <h3 class="Footer--info__title">Contact Us</h3>
            <div class="Footer--numbers">
                <span>+15409704919</span>
                <span>+15409157456</span>
            </div>
            <span class="Footer--info__email">test@test.com</span>
        </div>
        <div class="Footer--socials">
            <!-- <p class="Footer--socials__text">
                You can follow or write us for us differents social networks
            </p> -->
            <div class="Footer--socials-links">
                <a
                    class="Footer--social"
                    href="https://www.facebook.com/profile.php?id=100082903073712"
                    target="_blanck"
                >
                    <span class="Footer--social__link">
                        <Facebook size="24" fill="#fff" />
                    </span>
                    @Table Taste
                </a>
                <a
                    class="Footer--social"
                    href="https://www.instagram.com/table_taste_/"
                    target="_blanck"
                >
                    <span class="Footer--social__link">
                        <Instagram size="24" fill="#fff" />
                    </span>
                    @table_taste_
                </a>
            </div>
        </div>
    </div>
</footer>

<style>
    .Footer {
        padding: 2rem 0;
        background-color: #232930;
        color: #fff;
    }
    .Footer--container {
        width: 80%;
        margin: 0 auto;
        display: grid;
        gap: 2rem;
    }
    .Footer--info {
        font-size: 1.4rem;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        gap: 1rem;
    }
    .Footer--info__title {
        font-weight: 500;
    }
    .Footer--numbers {
        display: grid;
    }
    .Footer--socials__text {
        margin-bottom: 2rem;
    }
    .Footer--socials-links {
        display: grid;
        gap: 1rem;
    }
    .Footer--social {
        display: flex;
        align-items: center;
        gap: 1rem;
        text-decoration: none;
        color: #fff;
        font-size: 1.4rem;
    }
    .Footer--social__link {
        display: inline-flex;
        padding: 0.5rem;
        border: 1px solid #fff;
        border-radius: 2px;
    }
    @media screen and (min-width: 768px) {
        .Footer--container {
            width: 80%;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 30% 65%;
        }
    }
</style>
