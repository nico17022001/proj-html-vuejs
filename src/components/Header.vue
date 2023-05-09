<script>
export default {
  name:'Header'
  
}
</script>

<template>
  <!-- CONTENITORE HEADER -->
  <div id="main-wrapper">
    <!-- CONTENITORE INFO  -->
    <div id="header-info-container">
      <!-- LOGO -->
      <div id="logo-box">Logo</div>
      <!-- BOTTONI HEADER A DESTRA  -->
      <div id="buttons-container">
        <!-- CARRELLO -->
        <div id="cart">Carrello</div>
        <div id="menu">Menu a tendina</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    background-color: black;
    padding:0px 150px;
    height: 96px;
  }#header-info-container{
    display: flex ;
    background-color: bisque;
    justify-content: space-between;
    height: 100%;
  }#logo-box{
    color: white;
    background-color: aquamarine;
  }#buttons-container{
    color: white;
    background-color: rgb(36, 27, 111);
    display: flex;
  }#cart{
    background-color: yellow;
  }#menu{
    background: yellow;
  }
</style>