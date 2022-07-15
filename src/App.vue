<template>
  <div id="app">

    <FooterMain>
      <FooterList/>
    </FooterMain>
      
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import FooterMain from './components/FooterMain.vue'
import FooterList from './components/FooterList.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    FooterMain,
    FooterList
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
  margin-top: 60px;
}
</style>
