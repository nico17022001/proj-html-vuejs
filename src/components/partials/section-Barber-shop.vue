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
      <div id="title">Titolo sezione</div>
      <!-- LINEA DIVISORIA  -->
      <div id="brown-line">linea divisoria</div>
      <!-- SCRITTA IN GRIGIO CHIARO -->
      <div id="min-title">Titolo in grigio</div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-color: lightgray;
  }#container{
    margin-left:184px;
    background-color: burlywood;
    width: 650px;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }#title{
    background-color: rgb(23, 20, 213);
  }#brown-line{
    background-color: aqua;
  }#min-title{
    background-color: brown;
  }
</style>