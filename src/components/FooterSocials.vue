<template>
  <div id="footerS">
    <div class="container-lg">
      <div class="row justify-content-between align-items-center">
        <div class="col-2 ">
          <a class="sign-up-btn" href="#">SIGN-UP NOW</a>
        </div>
        <div id="socials-right" class="col-4 d-flex flex-row align-items-center p-4">
          <h5>Follow us!</h5>
          <ul class="d-flex align-items-center">
            <li>
              <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="">
              </a>
            </li>
              <li>
              <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="">
              </a>
            </li>
              <li>
              <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="">
              </a>
            </li>
              <li>
              <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="">
              </a>
            </li>
              <li>
              <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="">
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style leng="scss" scoped>
@import '../assets/style/variables.scss';


#footerS{
background-color: #303030;
 

};

ul{
  padding:0;
  margin: 0;
 
}

h5{
  color: #0c7cec;
}
li{
  margin-left:1rem;
}
.sign-up-btn{
  padding: 1rem;
  border: 2px solid #0c7cec;
  color: white;
  text-decoration: none;
}
</style>