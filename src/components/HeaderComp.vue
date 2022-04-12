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
        border: 2px solid skyblue;
        padding: 1rem;
    }
</style>