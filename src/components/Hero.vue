<template>
    <section class="Hero">
        <div class="Hero__background"></div>
        <div class="Hero__background Hero__background--lower"></div>
        <div class="Hero__wrapper">
            <div class="container">
                <div class="Hero__inner">
                    <h1>Kim Larsson</h1>
                    <p class="preamble">
                        Donec nec justo eget felis facilisis fermentum.
                        Aliquam porttitor mauris sit amet orci.
                        Aenean dignissim pellentesque felis.
                        Aliquam porttitor mauris sit amet orci.
                        Aenean dignissim pellentesque felis.
                    </p>
                </div>
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
    min-height: 60vh;
    position: relative;
    display: flex;
    &__wrapper {
        width: 100%;
        display: flex;
        align-items: center;
    }
    &__background {
        display: block;
        width: 120vw;
        left: -10vw;
        top: -15vh;
        position: absolute;
        background: linear-gradient(to right, #4b6cb7, #182848);
        height: 120%;
        transform: rotate(-5deg);
        &--lower {
            opacity: 0.2;
            top: -12vh;
            transform: rotate(-7deg);
        }
    }
    &__inner {
        padding: 120px 0;
        text-align: center;
        position: relative;
        z-index: 1;
        color: #ffffff;
        width: 800px;
        margin: 0 auto;
        max-width: 100%;
        margin-bottom: 3vh;
    }
}
</style>
