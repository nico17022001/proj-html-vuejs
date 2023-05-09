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
      <div id="logo-box"><img src="../assets/img/img-header/logo.png" alt=""></div>
      <!-- BOTTONI HEADER A DESTRA  -->
      <div id="buttons-container">
        <!-- CARRELLO -->
        <div id="cart"><i class="fa-solid fa-cart-shopping"></i></div>
        <div id="menu"><i class="fa-solid fa-bars"></i></div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    background-color: #000;
    padding:0px 150px;
    height: 96px;
    position: fixed;
    top: 0px;
    width: 100%;
  }#header-info-container{
    display: flex ;
    justify-content: space-between;
    height: 100%;
  }#logo-box{
    padding: 10px;
    width: 210px;
  }img{
    width: 100%;
    height: 100%;
  }
  
  #buttons-container{
    display: flex;
    align-items: center;
  }#cart{
    margin-right: 20px;
    color: white;
  }i{
    font-size: x-large;
    cursor: pointer;
  }#menu{
    color: #be9359;
  }
</style>