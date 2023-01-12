<div class="About-us">
    <div class="About-us--container">
        <div class="About-us--title">
            <h3 class="About-us--title__text">About Us</h3>
            <div class="About-us--info">
                <img
                    src="/img/about-us.png"
                    alt=""
                    class="About-us--title__img"
                />
                <p class="About-us--info__text">
                    At Table Taste we are dedicated to transforming cuisine into
                    edible art. You will enjoy an experience of exquisite
                    morsels, breaking the monotony of traditional food and
                    leaving the diner enchanted at the “Tabel Taste”.
                </p>
            </div>
        </div>
    </div>
</div>

<style>
    .About-us {
        background-color: #e1b12c;
        padding: 2rem 0;
    }
    .About-us--container {
        width: 80%;
        margin: 0 auto;
        display: grid;
        text-align: center;
    }
    .About-us--title__text {
        font-size: 1.5rem;
        margin-bottom: 1.5rem;
    }
    .About-us--title__img {
        margin-bottom: 1.5rem;
    }
    .About-us--info__text {
        font-weight: 500;
        font-size: 1.2rem;
    }
    @media screen and (min-width: 768px) {
        .About-us--container {
            width: 80%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            text-align: initial;
        }
        .About-us--title__img {
            margin-bottom: initial;
        }
        .About-us--info {
            display: grid;
            grid-template-columns: auto 1fr;
            gap: 3rem;
        }
    }
</style>
