<script>
export default {
  name:'barberShop'
}
</script>

<template>
  <!-- CONTENITORE IMMAGINE SFONDO -->
  <div id="main-wrapper">
    <!-- CONTENITORE DEGLI ELEMENTI  -->
    <div id="container">
      <!-- TITOLO -->
      <div id="title"><h1>Barber Shop</h1></div>
      <!-- LINEA DIVISORIA  -->
      <div id="brown-line"></div>
      <!-- SCRITTA IN GRIGIO CHIARO -->
      <div id="min-title">The Pinnacle of Male Grooming</div>
      <!-- LEARN MORE container -->
      <div id="learn-container">
        <span><strong>LEARN MORE</strong></span>
      </div>
    </div>

    <div id="img-container"></div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-image: url(../../assets/img/img-main/sfondo.jpg);
    background-size: cover;
    display: flex;
    margin-top: 96px;
  }#container{
    margin-left:184px;
    width: 650px;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }#title{
    color: white;
    font-size: xxx-large;
    margin-bottom: 5px;
  }#brown-line{
    background-color: #be9359;
    height: 4px;
    width: 257px;

  }#min-title{
    margin: 40px 0px;
    font-size: x-large;
    color: #b0b0b0;;
  }

  #learn-container{
    color: #be9359;
    font-size: large;
    border: solid 2px #be9359;
    width: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 15px 10px;
    cursor: pointer;
  }

  #img-container{
    background-image: url(../../assets/img/img-main/persona.png);
    width: 650px;
    height: 100%;
    background-size:contain;
    background-position:right ;
    background-repeat:no-repeat ; 
  }
</style>