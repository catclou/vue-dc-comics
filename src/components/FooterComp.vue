<template>
    <footer>
        <button>sign-up now!</button>
        <FollowUsComp/>
    </footer>
</template>

<script>

import FollowUsComp from './FollowUsComp.vue'

export default {
    name: 'FooterComp',
    components: {
        FollowUsComp
    }
}
</script>

<style scoped lang="scss">

    @import '../style/variabili.scss';

    footer {
        background-color: #303030;
        display: flex;
        justify-content: space-around;
        padding: 25px;
    }

    button {
        text-transform: uppercase;
        background-color: transparent;
        color: white;
        border: 2px solid $dc-blue;
        padding: 10px;
        font-weight: 500;
    }

</style>