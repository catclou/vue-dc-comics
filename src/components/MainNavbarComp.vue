<template>
    <nav>
        <ul>
            <li> <a href="#">characters</a> </li>
            <li> <a href="#">comics</a> </li>
            <li> <a href="#">movies</a> </li>
            <li> <a href="#">tv</a> </li>
            <li> <a href="#">games</a> </li>
            <li> <a href="#">collectibles</a> </li>
            <li> <a href="#">videos</a> </li>
            <li> <a href="#">fans</a> </li>
            <li> <a href="#">news</a> </li>
            <li> <a href="#">shop</a> </li>
        </ul>
    </nav>
</template>

<script>


export default {
    name: 'MainNavbarComp',
}
</script>

<style scoped lang="scss">
    ul {
        display: flex;
        align-items: center;

        li {
        padding: 1rem;
        list-style: none;
        align-self: center;
        text-transform: uppercase;
        font-weight: bold;
        color: black;
        }
    }

    a {
        text-decoration: none;
        color: black;
        padding-bottom: 4rem;

        &:hover {
            color: #0282f9;
            border-bottom: 5px inset #0282f9;
        }
    }
</style>