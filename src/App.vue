<template>
  <div id="app">
    <HeaderComp/>
    <FooterMain/>
  

      
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import FooterMain from './components/FooterMain.vue'



export default {
  name: 'App',
  components: {
    HeaderComp,
    FooterMain,
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "~assets/style/variables.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  max-width: 1000px;
  margin:0 auto;
}
</style>
