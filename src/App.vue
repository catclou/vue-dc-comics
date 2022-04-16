<template>
  <div id="app">
    <HeaderComp/>
    <ContentComp/>
    <IconLinksComp/>
    <LinksComp/>
    <FooterComp/>
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import ContentComp from './components/ContentComp.vue'
import IconLinksComp from './components/IconLinksComp.vue'
import LinksComp from './components/LinksComp.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    IconLinksComp,
    LinksComp,
    FooterComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
