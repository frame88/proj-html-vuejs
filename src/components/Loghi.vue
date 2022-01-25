<template>
    <div class="container-max foto">
        <div class="container loghi">
            <img src="../assets/img/amazon.svg" alt="">
            <img src="../assets/img/google.svg" alt="">
            <img src="../assets/img/lenovo.svg" alt="">
            <img src="../assets/img/paypal.svg" alt="">
            <img src="../assets/img/shopify.svg" alt="">
            <img src="../assets/img/spotify.svg" alt="">
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

.foto {
    border-top: 2px solid $grigio;
    background-color: $bianco-2;
    padding-top: 2em;
    padding-bottom: 2em;
    border-radius: 0 0 50% 50%;
}

.loghi {
    height: 100%;

}

.loghi img {
    width: 6%;
    

}

.loghi {
    display: flex;
    justify-content: space-around;
}


</style>