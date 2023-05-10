
<script>
export default {
  name:'proBarbers'
}
</script>

<template>
  <!-- CONTENITORE CON SFONDO -->
  <div id="main-wrapper">
    <!-- CONTENITORE INFO SEZIONE -->
    <div id="container">
      <!-- ELEMENTI SEZIONE -->
      <div id="award-container">AWARD WINNING</div>
      <div id="pro-container"><h1>Pro Barbers</h1></div>
      <div id="meet-container">MEET YOUR NEW BARBER</div>
    </div>
    <!-- CONTENITORE SVG PER SFONDO -->
    <div id="svg-container"><svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#ffffff;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg></div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-image: url(../../assets/img/img-main/marlborobg.jpg);
    flex-direction: column;
    display: flex;
    justify-content: center;
    align-items: center;
    background-size: cover;
  }#container{
    height: 100%;
    width: 650px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }#award-container{
    color: #be9359;
    font-size: x-large;
  }#pro-container{
    color: #B0B0B0;
    font-size: xxx-large;
  }#meet-container{
    color: #be9359;
    border: solid 2px #be9359;
    padding: 15px 50px;
    font-size: x-large;
    margin-top: 30px;
    cursor: pointer;
  }

#svg-container{
  height: 100px;
  width: 100%;
}
</style>