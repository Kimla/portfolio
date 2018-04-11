<template>
    <div id="app">
        <Home></Home>
    </div>
</template>

<script>
import Home from './views/Home.vue';

export default {
    components: {
        Home,
    },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700');
@import './style/main.scss';

#app {
    overflow: hidden;
}
</style>

