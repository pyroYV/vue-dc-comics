<template>
  <div id="footer-main">
    <div class="container-lg">
    <FooterList/>
      <div class="position-absolute" id="logo-bg">
      <img src="../assets/img/dc-logo-bg.png" alt="dclogo">
      </div>
      </div>
  </div>
</template>

<script>
import FooterList from './FooterList.vue'

export default {
    components: {
    FooterList,
  }
}
</script>

<style lang="scss" scoped>
  
#footer-main{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-height: 400px;
    position:relative;
      overflow: hidden;
    #logo-bg{
      right: 160px;
      top:-50px;
      
      img{
        height: 400px;
      }
    }

}

</style>