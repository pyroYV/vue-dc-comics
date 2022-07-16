<template>
  <footer>
    <FooterList/>
  </footer>
</template>

<script>
import FooterList from './FooterList.vue'
import FooterSocials from './FooterSocials.vue'

export default {
    components: {
    FooterList,
    FooterSocials
  }
}
</script>

<style lang="scss" scoped>
footer{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-height: 450px;
    padding-left:50px;

}

</style>