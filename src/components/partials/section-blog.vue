<script>
export default {
name:'blog'
}
</script>
<template>
  <!-- CONTENITORE SVG -->
  <div id="main-wrapper">
    <div id="svg"><svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg></div>

    <!-- CONTENITORE DEL TITOLO DI SEZIONE -->
    <div id="container">
      <div id="what"><span>TALES FROM THE BARBER SHOP</span></div>
      <div id="title"><h2>Recent Blog Posts</h2></div>
    </div>

    <div id="reviews-box">
      <!-- CARD -->
      <div class="card">
        <!-- IMMAGINE CARD -->
        <div class="card-img"><img src="../../assets/img/img-main/negozio-colorato.jpg" alt=""></div>
        <!-- TITOLO CARD -->
        <div class="card-title"><strong>Avada Barbers Now Open</strong></div>
        <!-- TESTO CARTA -->
        <div class="card-text">
          <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut dapibus magna. Praesent semper,</span>
        </div>
      </div>

      <!-- CARD -->
      <div class="card">
        <!-- IMMAGINE CARD -->
        <div class="card-img"><img src="../../assets/img/img-main/sedia.jpg" alt=""></div>
        <!-- TITOLO CARD -->
        <div class="card-title"><strong>Choosing The Right Barber</strong></div>
        <!-- TESTO CARTA -->
        <div class="card-text">
          <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut dapibus magna. Praesent semper,</span>
        </div>
      </div>

      <!-- CARD -->
      <div class="card">
        <!-- IMMAGINE CARD -->
        <div class="card-img"><img src="../../assets/img/img-main/taglio.jpg" alt=""></div>
        <!-- TITOLO CARD -->
        <div class="card-title"><strong>Quick Service Guide</strong></div>
        <!-- TESTO CARTA -->
        <div class="card-text">
          <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut dapibus magna. Praesent semper,</span>
        </div>
      </div>
    </div>

    <!-- CONTENITORE READ -->
    <div id="read-container">
      <div id="read">Read More From Our Blog</div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
  #main-wrapper{
    width: 100%;
    background-color: whitesmoke;
  }#svg{
    margin-bottom: 70px;
  }svg{
    transform: rotate(180deg);
  }#container{
    display: flex;
    flex-direction:column ;
    justify-content: center;
    align-items: center;
  }#what{
    color: #be9359;
  }#title{
    color: #b0b0b0;
    font-size: xxx-large;
  }

  #reviews-box{
    width: 100%;
    display: flex;
    justify-content: center;
    padding: 0px 200px;
    margin-top: 40px;
  }.card{
    width: calc(100% / 3);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0px 15px;
  }.card-img img{
    width: 100%;
    transition: transform .5s;
    cursor: pointer;
  }
  
  .card-img img:hover{
    transform: scale(1.04);
  }
  .card-title{
    color: #be9359;
    font-size: xx-large;
    text-align: center;
    padding: 0px 10px;
    margin: 10px 0px;
  }.card-text{
    color: gray;
    text-align: center;
    padding: 0px 18px;
  }

  #read-container{
    display: flex;
    justify-content: center;
    cursor: pointer;
  }#read{
    border: solid 2px #be9359 ;
    display: flex;
    align-items: center;
    color: #be9359;
    padding: 10px 46px;
    margin: 50px 0px;
  }

</style>