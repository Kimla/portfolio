<template>
    <div class="Card">
        <div class="Card__imageHolder">
            <img src="https://cdn.dribbble.com/users/27547/screenshots/4447683/article-interaction.gif" alt="" class="Card__image ab100 objectFitCover">
        </div>
        <div class="Card__content">
            <h2 class="Card__heading">Lorem ipsum</h2>
            <p class="Card__text">
                Sed egestas, ante et vulputate volutpat,
                eros pede semper est, vitae luctus metus
                libero eu augue. Morbi purus libero, faucibus adipiscing,
                commodo quis, gravida id, est. Sed lectus.
                Praesent elementum hendrerit tortor.
                Sed semper lorem at felis. Vestibulum volutpat,
                lacus a ultrices sagittis, mi neque euismod dui,
                eu pulvinar nunc sapien ornare nisl. Phasellus pede arcu,
                dapibus eu, fermentum et, dapibus sed, urna.
            </p>
        </div>
    </div>
</template>

<script>
export default {

};
</script>

<style lang="scss">
.Card {
    display: flex;
    flex-wrap: wrap;
    margin-bottom: 100px;
    &__imageHolder {
        position: relative;
        height: 500px;
        width: 100%;
        margin-right: auto;
        box-shadow: 0 5px 15px rgba(0,0,0,.2);
    }
    &__image {
        width: 100%;
    }
    &__content {
        width: calc(100% - 300px);
        background: #ffffff;
        padding: 50px;
        margin: 0 auto;
        margin-top: -30px;
        position: relative;
        z-index: 1;
        box-shadow: 0 5px 15px rgba(0,0,0,.2);
    }
}
</style>
