<template>
    <footer>
        <ListFooterComp/>
        <img src="../assets/img/dc-logo-bg.png" alt="DC logo">
    </footer>
</template>

<script>

import ListFooterComp from './ListFooterComp.vue'

export default {
    name: 'LinksComp',
    components: {
        ListFooterComp,
    }
}
</script>

<style scoped lang="scss">
    footer {
        display: flex;
        justify-content: space-around;
        padding-top: 1rem;
        background-image: url('../assets/img/footer-bg.jpg');
    }

    img {
        margin: -5%;
        height: 25rem;
    }

</style>