<template>
  <div id="app">
    <HeaderComp/>
    <Hero/>
    <HeroNav/>
    <FooterMain/>
    <FooterSocials/>
    

      
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import FooterMain from './components/FooterMain.vue'
import Hero from './components/Hero.vue'
import FooterSocials from './components/FooterSocials.vue'
import HeroNav from './components/HeroNav.vue'



export default {
  name: 'App',
  components: {
    HeaderComp,
    Hero,
    FooterMain,
    FooterSocials,
    HeroNav,
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
  color:white;
 
}
</style>
