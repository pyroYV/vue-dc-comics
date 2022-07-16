<template>
  <footer>
    <FooterList/>
    <div class="position-absolute" id="logo-bg">
    <img src="../assets/img/dc-logo-bg.png" alt="dclogo">
    </div>
  </footer>
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
  
footer{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-height: 400px;
    padding-left:50px;
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