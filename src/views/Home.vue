<template>
    <div>
        <Hero></Hero>
        <div class="cards">
            <div class="container">
                <Card></Card>
                <Card></Card>
                <Card></Card>
                <Card></Card>
            </div>
        </div>
    </div>
</template>

<script>
import Hero from '../components/Hero.vue';
import Card from '../components/Card.vue';

export default {
    name: 'home',
    components: {
        Hero,
        Card,
    },
};
</script>

<style lang="scss">
.cards {
    margin-top: 150px;
    padding-bottom: 50px;
}
</style>
