<header class="Header">
    <div class="Header--title">
        <h1 class="Header--title__name">Welcome to Table Taste</h1>
        <h2 class="Header--title__text">Catering & Charcuterie</h2>
    </div>
</header>

<style>
    .Header {
        background: linear-gradient(
                0deg,
                rgba(0, 0, 0, 0.5),
                rgba(0, 0, 0, 0.5)
            ),
            url("/img/headerMobile.jpg");
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-size: cover;
        height: 100vh;
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: "Square Peg", cursive;
    }

    @media screen and (min-width: 768px) {
        .Header {
            background: linear-gradient(
                    0deg,
                    rgba(0, 0, 0, 0.5),
                    rgba(0, 0, 0, 0.5)
                ),
                url("/img/header.jpg");
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
        }
    }

    .Header--title {
        text-align: center;
        font-weight: normal;
    }
    .Header--title__name {
        font-size: 5rem;
        font-weight: normal;
    }
    .Header--title__text {
        font-size: 4rem;
        font-weight: normal;
    }
</style>
