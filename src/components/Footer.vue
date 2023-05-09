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
        <div class="img-container">IMG</div>
        <div class="text-container">testo della carta</div>
      </div>
      <!-- CENTRALE -->
      <div id="main-aside">
        <div id="img-main">IMG</div>
        <div id="info-main">
          <div>informazione</div>
          <div>informazione</div>
          <div>informazione</div>
          <div>informazione</div>
          <div>informazione</div>
        </div>
        <div id="follow-container">FOLLOW US</div>
        <!-- CONTENITORE DEI SOCIAL -->
        <div id="social-container">social</div>
      </div>
      <!-- LATO DESTRO  -->
      <div class="aside">
        <div class="img-container">IMG</div>
        <div class="text-container">testo della carta</div>
      </div>
    </div>
    <div id="info-bar">
      <div id="info"><span>INFO</span></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-color: darkblue;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }#main{
    width: 80%;
    height: 100%;
    background-color: aqua;
    display: flex;
  }.aside{
    width: 30%;
    height: 100%;
    background-color: aquamarine;
    border: solid 1px black;
  }#main-aside{
    width: 40%;
    height: 100%;
    background-color: darkmagenta;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
  }.img-container{
    height: 80%;
    background-color: springgreen;
  }.text-container{
    height: 20%;
    background-color: crimson;
  }#info-bar{
    background-color: cadetblue;
    height: 110px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>