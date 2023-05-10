
<script>
export default {
  name:'avada'
}
</script>

<template>
  <div id="main-wrapper">
    <div id="container">
      <!-- ELEMENTI SEZIONE -->
      <div id="have-container"><span><strong>WE HAVE YOU COVERED</strong></span></div>
      <div id="avada-container"><h2>Avada Grooming Products</h2></div>
    </div>

    <!-- CONTENITORE TESTO ED IMMAGINI -->
    <div id="service-box">
      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/brush.png"></div>
        <div class="card-title"><h4>Brush</h4></div>
        <div class="card-price"><span>$15.00</span></div>
      </div>
      
      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/scissors.png" alt=""></div>
        <div class="card-title"><h4>Scissors</h4></div>
        <div class="card-price"><span>$85</span></div>
      </div>

      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/hot_oil_dark.png" alt=""></div>
        <div class="card-title"><h4>Hot Oil</h4></div>
        <div class="card-price"><span>$15</span></div>
      </div>

      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/razor.png" alt=""></div>
        <div class="card-title"><h4>Straight Razor</h4></div>
        <div class="card-price"><span>$15</span></div>
      </div>
    </div>
    
    <!-- CONTENITORE READ -->
    <div id="shop-container">
      <div id="shop"><h4>SHOP OUR PRODUCT RANGE</h4></div>
    </div>

    <div id="container-section">
    <!-- SECTION CONTAINER -->
      <div id="section-container">
        <!-- LATO SINISTRO SEZIONE -->
        <div id="section-img-container">
          <img src="../../assets/img/img-main/shaving_butter.png" alt="">
        </div>
        <!-- LATO DESTRO SEZIONE -->
        <div id="section-info-container">
          <!-- SCRITTA GIALLA -->
          <div id="this-month"><span>THIS MONTHS FEATURED PRODUCT</span></div>
          <!-- TITOLO SEZIONE -->
          <div id="section-title"><h2>Shaving Butter</h2></div>
          <!-- TESTO SEZIONE -->
          <div id="section-text">
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque laoreet enim est, vel molestie dolor ultrices ut. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
          </div>
          <!-- BOTTONE SEZIONE -->
          <div id="buy-now">
            <span>BUY NOW</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped> 
  #main-wrapper{
    background-image: url(../../assets/img/img-main/taglio-barba.jpg);
    background-size: cover;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }#container{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100px;
    margin-top: 60px;
  }#have-container{
    color: #be9359;
    margin-top: 50px;
  }#avada-container{
    color:#b0b0b0;
    font-size: xxx-large;
  }

  #service-box{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0px 200px;
  }.card{
    width: calc(100% / 4);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-top: 50px;
  }.card-title{
    color: #be9359;
    font-size: xx-large;
    margin-top: 10px;
  }.card-price{
    color: #be9359;
    margin-top: 10px;
  }img{
    width: 320px;
  }

  #shop-container{
    border: solid 2px #be9359;
    display: flex;
    justify-content: center;
    margin: 70px 0px 140px 0px;
    color: #be9359;
    padding: 15px 60px;
    cursor: pointer;
  }#shop{
    display: flex;
    align-items: center;
  }

  #container-section{
    width: 80%;
    background-color: blue;
    position: relative;
  }#section-container{
    width: 100%;
    height: 400px;
    background-color: yellow ;
    position: absolute;
    bottom: -345px;
    display: flex;
    border-top: 5px solid #be9359;
  }#section-img-container{
    width: 35%;
    height: 100%;
    background-color: brown;
    background-image: url(../../assets/img/img-main/sfondo-crema.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
  }#section-info-container{
    width: 65%;
    height: 100%;
    background-color: black;
    padding: 80px;
  }#this-month{
    color: #be9359;
    font-size: large;
  }#section-title{
    color: #b0b0b0;
    font-size: xxx-large;
  }#section-text{
    color: #9f9f9f;
    font-size: large;
    width: 533px;
    margin-top: 30px;
  }#buy-now{
    color: #be9359;
    border: solid 2px #be9359;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 178px;
    padding: 10px 25px;
    margin-top: 30px;
    cursor: pointer;
  }

</style>