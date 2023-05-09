<script>
export default {
name:'blog'
}
</script>
<template>
  <!-- CONTENITORE SVG -->
  <div id="main-wrapper">
    <div id="svg">SVG</div>

    <!-- CONTENITORE DEL TITOLO DI SEZIONE -->
    <div id="container">
      <div id="what"><span>WHAT PEOPLE SAY</span></div>
      <div id="title"><h2>Reviews</h2></div>
    </div>

    <div id="reviews-box">
      <!-- CARD -->
      <div class="card">
        <!-- IMMAGINE CARD -->
        <div class="card-img">IMG</div>
        <!-- TITOLO CARD -->
        <div class="card-title">Titolo</div>
        <!-- TESTO CARTA -->
        <div class="card-text">
          <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum nulla ex quod ullam adipisci suscipit repudiandae? Eaque voluptatem nesciunt voluptatibus, veritatis corporis ipsum amet voluptatum quidem, deleniti illum optio consectetur!</span>
        </div>
      </div>

      <!-- CARD -->
      <div class="card">
        <!-- IMMAGINE CARD -->
        <div class="card-img">IMG</div>
        <!-- TITOLO CARD -->
        <div class="card-title">Titolo</div>
        <!-- TESTO CARTA -->
        <div class="card-text">
          <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum nulla ex quod ullam adipisci suscipit repudiandae? Eaque voluptatem nesciunt voluptatibus, veritatis corporis ipsum amet voluptatum quidem, deleniti illum optio consectetur!</span>
        </div>
      </div>

      <!-- CARD -->
      <div class="card">
        <!-- IMMAGINE CARD -->
        <div class="card-img">IMG</div>
        <!-- TITOLO CARD -->
        <div class="card-title">Titolo</div>
        <!-- TESTO CARTA -->
        <div class="card-text">
          <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum nulla ex quod ullam adipisci suscipit repudiandae? Eaque voluptatem nesciunt voluptatibus, veritatis corporis ipsum amet voluptatum quidem, deleniti illum optio consectetur!</span>
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
    height: 500px;
    width: 100%;
    background-color: lightgray;
  }#svg{
    background-color: aqua;
    height: 50px;
  }#container{
    display: flex;
    flex-direction:column ;
    justify-content: center;
    align-items: center;
  } 

  #reviews-box{
    height: 200px;
    width: 100%;
    background-color: green ;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0px 200px;
  }.card{
    width: calc(100% / 3);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }

  #read-container{
    height: 100px;
    background-color: burlywood;
    display: flex;
    justify-content: center;
  }#read{
    height: 100%;
    background-color: red;
    display: flex;
    align-items: center;
  }

</style>