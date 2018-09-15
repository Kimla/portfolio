<template>
    <div>
        <Hero></Hero>
    </div>
</template>

<script>
import Hero from '../components/Hero.vue';

export default {
    name: 'home',
    components: {
        Hero,
    },
};
</script>

<style lang="scss">
.cards {
    margin-top: 15vh;
    padding-bottom: 50px;
}
</style>
