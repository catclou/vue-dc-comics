<template>
    <nav>
        <ul>
            <li>characters</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
            <li>games</li>
            <li>collectibles</li>
            <li>videos</li>
            <li>fans</li>
            <li>news</li>
            <li>shop</li>
        </ul>
    </nav>
</template>

<script>


export default {
    name: 'MainNavbarComp',
}
</script>

<style scoped>
    ul {
        display: flex;
        align-items: center;
    }

    li {
        padding: 1rem;
        list-style: none;
        align-self: center;
        text-transform: uppercase;
        font-weight: bold;
        padding-bottom: 2rem;
        /* aggiungere border-bottom e color blue all'hover */
        /* border-bottom: 2px solid blue; */
    }
</style>