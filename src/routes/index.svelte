<script>
    import Header from "$lib/elements/Header.svelte";
    import Gallery from "$lib/elements/Gallery.svelte";
    import AboutUs from "$lib/elements/AboutUs.svelte";
    import Menu from "$lib/elements/Menu.svelte";
    import Footer from "$lib/elements/Footer.svelte";
    import Copy from "$lib/elements/Copy.svelte";
    import Facebook from "$lib/svg/icons/Facebook.svelte";
</script>

<Header />
<div class="Index--container">
    <Gallery />
    <AboutUs />
    <Menu />
    <Footer />
    <Copy />
    <div class="Facebook-btn">
        <a
            href="https://www.facebook.com/profile.php?id=100082903073712"
            class="Facebook-btn__link"
            target="_blanck"
        >
            <Facebook size="24" fill="#fff" />
        </a>
    </div>
</div>

<style>
    .Index--container {
        position: relative;
    }
    .Facebook-btn {
        position: sticky;
        bottom: 1rem;
        left: 100%;
        display: inline-block;
        padding: 0 1rem;
    }
    .Facebook-btn__link {
        border-radius: 50%;
        background-color: #3b5998;
        width: auto;
        display: inline-flex;
        padding: 1rem;
    }
</style>
