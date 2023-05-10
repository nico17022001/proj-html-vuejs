<script>
export default {
  name:'Footer'
  
}
</script>

<template>
  <div id="main-wrapper">
    <div id="main">
      <!-- LATO SINISTRO -->
      <div class="aside">
        <div class="img-container"><img src="../assets/img/img-footer/avadabarbers_footer_shop_image-400x312.png" alt=""></div>
        <div class="text-container">
          <div class="aside-text">SHOP OUR RANGE NOW</div>
        </div>
      </div>
      <!-- CENTRALE -->
      <div id="main-aside">
        <div id="img-main"><img src="../assets/img/img-footer/avadabarbers-logo.png" alt=""></div>
        <div id="info-main">
          <div class="gray">Avada Barbers</div>
          <div class="gray">123 New York Street</div>
          <div class="gray">New York City</div>
          <div class="gray">info@yourwebsite.com</div>
          <div class="gray">+1 (555) 555-1212</div>
        </div>
        <div id="follow-container">FOLLOW US</div>
        <!-- CONTENITORE DEI SOCIAL -->
        <div id="social-container">
          <i class="fa-brands fa-facebook-f"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
        </div>
      </div>
      <!-- LATO DESTRO  -->
      <div class="aside">
        <div class="img-container"><img class="reverse" src="../assets/img/img-footer/taglio.png" alt=""></div>
        <div class="text-container">
          <div class="aside-text">BOOK YOUR APPOINTMENT</div>
        </div>
      </div>
    </div>
    <div id="info-bar">
      <div id="info"><span>© Copyright 2012 - 2023 | <a href="" class="orange">Avada Theme by ThemeFusion</a> | All Rights Reserved | Powered by <a href="" class="orange">WordPress</a> </span></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-color: #0f0f0f;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }#main{
    width: 80%;
    height: 100%;
    display: flex;
  }.aside{
    width: 30%;
    height: 100%;
  }.aside-text{
    color: #be9359;
    border: solid 2px #be9359;
    width: 250px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px;
    cursor: pointer;
  }#main-aside{
    width: 40%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
  }#follow-container{
    color:#be9359;
  }#info-main .gray{
    color: grey;
    font-size: large;
    text-align: center;
    margin: 5px 0px;
    cursor: pointer;
  }#img-main{
    width: 180px;
  }.img-container{
    height: 80%;
    display: flex;
    justify-content: center;
  }img{
    object-fit: contain;
  height: 100%;
  width: 100%;
}.text-container{
    height: 20%;
    display: flex;
    justify-content: center;
    align-items: center;
  }#info-bar{
    background-color: #171717;
    height: 110px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  #social-container i{
    color: gray;
    cursor: pointer;
    margin: 0px 10px;
  }

  #social-container i:hover{
    color: rgba(128, 128, 128, 0.715);
  }

  #info-main .gray:hover{
    color: white;
  }
  .reverse{
    transform: scaleX(-1);
    width: 200px;
  }

  #info{
    font-size: small;
    color: gray;
  }

  .orange{
    color: #be9359;
    text-decoration: none;
  }
</style>