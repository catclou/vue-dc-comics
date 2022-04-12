<template>
    <div>
        <div class="fake-li"> <img src="../assets/img/buy-comics-digital-comics.png" alt=""> digital comics</div>
        <div class="fake-li"> <img src="../assets/img/buy-comics-merchandise.png" alt=""> dc merchandise</div>
        <div class="fake-li"> <img src="../assets/img/buy-comics-subscriptions.png" alt=""> subscription</div>
        <div class="fake-li"> <img src="../assets/img/buy-comics-shop-locator.png" alt=""> comic shop locator</div>
        <div class="fake-li"> <img class="visa" src="../assets/img/buy-dc-power-visa.svg" alt=""> dc power visa</div>
    </div>
</template>

<script>

export default {
    name: 'IconLinksComp',
    components: {
    // EventualeNomeComponenteInterna
    }
}
</script>

<style scoped>
    div {
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #0282f9;
    }

    .fake-li {
        padding: 1rem;
        align-self: center;
        text-transform: uppercase;
        padding: 4rem;
        color: white;
    }

    .visa {
        width: 60px;
    }

    img {
        height: 50px;
        margin-right: 10px;
    }

</style>