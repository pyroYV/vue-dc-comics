<template>
  <div class="wrapper">
    <div class="p-4 container-lg d-flex justify-content-around">
        <div class="nav-item d-flex align-items-center">
          <a href="#">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="buyDigitalComics">
            <span>DIGITAL COMICS</span>
          </a>
        </div>
        <div class="nav-item d-flex align-items-center">
          <a href="#">
            <img src="../assets/img/buy-comics-merchandise.png" alt="buyMerchandise">
            <span>MERCHANDISE</span>
          </a>
        </div>
        <div class="nav-item d-flex align-items-center">
          <a href="#">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="buySubscriptions">
            <span>SUBSCRIPTIONS</span>
          </a>
        </div>
        <div class="nav-item d-flex align-items-center">
          <a href="#">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="buyDigitalComics">
            <span>SHOP LOCATOR</span>
          </a>
        </div>
        <div class="nav-item d-flex align-items-center">
          <a href="#">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="buyVisa">
            <span>DC POWER VISA</span>
          </a>
        </div>  
          
    </div>
  </div>

</template>

<script>
export default {

    
}
</script>

<style lang='scss' scoped>
@import '../assets/style/variables.scss'; 

.wrapper{
    background-color: $brand-color;
    .nav-item{
      margin-right: .8rem;
      img{
        height: 50px;
        margin-right: 10px;
      }
      a{
        color: white;
        text-decoration: none;
        font-size: 1rem;
      }
    }
}

</style>