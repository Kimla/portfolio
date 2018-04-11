<template>
    <section class="Hero">
        <div class="Hero__background"></div>
        <div class="Hero__background Hero__background--lower"></div>
        <div class="container">
            <div class="Hero__inner">
                <h1>HI!</h1>
                <p class="preamble">
                    Donec nec justo eget felis facilisis fermentum.
                    Aliquam porttitor mauris sit amet orci.
                    Aenean dignissim pellentesque felis.
                    Aliquam porttitor mauris sit amet orci.
                    Aenean dignissim pellentesque felis.
                </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {

};
</script>

<style lang="scss">
.Hero {
    &__background {
        display: block;
        width: 120vw;
        left: -10vw;
        top: -15vh;
        position: absolute;
        background: linear-gradient(to right, #085078, #85d8ce);
        min-height: 60vh;
        transform: rotate(-5deg);
        &--lower {
            opacity: 0.2;
            top: -10vh;
            transform: rotate(-7deg);
        }
    }
    &__inner {
        padding: 120px 0;
        text-align: center;
        position: relative;
        z-index: 1;
        color: #ffffff;
    }
    .container {
        width: 700px;
    }
}
</style>
