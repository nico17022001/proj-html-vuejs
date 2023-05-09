
<script>
export default {
  name:'avada'
}
</script>

<template>
  <div id="main-wrapper">
    <div id="container">
      <!-- ELEMENTI SEZIONE -->
      <div id="have-container">WE HAVE YOU COVERED</div>
      <div id="avada-container">Avada Grooming Products</div>
    </div>

    <!-- CONTENITORE TESTO ED IMMAGINI -->
    <div id="service-box">
      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-price"><span>15$</span></div>
      </div>
      
      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-price"><span>15$</span></div>
      </div>

      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-price"><span>15$</span></div>
      </div>

      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-price"><span>15$</span></div>
      </div>
    </div>
    
    <!-- CONTENITORE READ -->
    <div id="shop-container">
      <div id="shop">Shop Our Product Range</div>
    </div>

    <div id="container-section">
    <!-- SECTION CONTAINER -->
      <div id="section-container">
        <!-- LATO SINISTRO SEZIONE -->
        <div id="section-img-container"></div>
        <!-- LATO DESTRO SEZIONE -->
        <div id="section-info-container">
          <!-- SCRITTA GIALLA -->
          <div id="this-month"><span>THIS MONTH</span></div>
          <!-- TITOLO SEZIONE -->
          <div id="section-title"><h2>Shaving Butter</h2></div>
          <!-- TESTO SEZIONE -->
          <div id="section-text">
            <span>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deserunt iste, aliquid molestias, nulla</span>
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
    background-color: aqua;
    height: 500px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }#container{
    width: 800px;
    background-color: blanchedalmond;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100px;
  }

  #service-box{
    height: 200px;
    width: 100%;
    background-color: yellow ;
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
  }

  #shop-container{
    height: 100px;
    background-color: burlywood;
    display: flex;
    justify-content: center;
  }#shop{
    height: 100%;
    background-color: red;
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
    bottom: -450px;
    display: flex;
  }#section-img-container{
    width: 35%;
    height: 100%;
    background-color: brown;
  }#section-info-container{
    width: 65%;
    height: 100%;
    background-color: chartreuse;
    padding: 40px;
  }

</style>