<template>
    <section class="hero">
        <div class="container">
            <div class="inner">
                <h1 class="heading">Kim Larsson</h1>
                <p class="preamble">
                    <span class="text">Web developer @</span>&nbsp;
                    <a class="link" href="https://www.bravissimo.se/" target="_blank">Bravissimo</a>
                </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
};
</script>

<style lang="scss" scoped>
.hero {
    width: 100vw;
    height: 100vh;
    background-color: #202020;
    display: flex;
    align-items: center;
    justify-content: center;
}
.inner {
    text-align: center;
    padding-bottom: 5vh;
}
.heading {
    color: #ffffff;
    letter-spacing: 0.5px;
}
.preamble {
    color: #ffffff;
    font-size: 28px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.text {
    display: block;
}
.link {
    font-weight: 600;
    overflow: hidden;
    position: relative;
    display: block;
    padding: 3px 0;
    &::after {
        content: '';
        position: absolute;
        left: 0;
        bottom: 0;
        width: 100%;
        height: 3px;
        transform: translateX(-105%);
        background-color: #ffffff;
        transition: 0.2s;
    }
    &:hover::after {
        transform: translateX(0);
    }
}
</style>
