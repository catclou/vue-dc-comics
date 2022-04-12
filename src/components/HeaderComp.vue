<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="DC logo">
        <MainNavbarComp></MainNavbarComp>
    </header>
</template>

<script>

import MainNavbarComp from './MainNavbarComp.vue'

export default {
    name: 'HeaderComp',
    components: {
    MainNavbarComp
    }
}
</script>

<style scoped>
    header {
        display: flex;
        justify-content: space-around;
        padding-top: 1rem;
    }

    img {
        height: 100px;
        margin-bottom: 0;
        padding-bottom: 1.2rem;
    }
</style>