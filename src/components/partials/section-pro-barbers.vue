
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
      <div id="pro-container">Pro barbers</div>
      <div id="meet-container">MEET YOUR NEW BARBER</div>
    </div>
    <!-- CONTENITORE SVG PER SFONDO -->
    <div id="svg-container">SVG</div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-color: aqua;
    flex-direction: column;
    display: flex;
    justify-content: center;
    align-items: center;
  }#container{
    height: 100%;
    width: 650px;
    background-color: blanchedalmond;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }#award-container{
    background-color: coral;
  }#pro-container{
    background-color: cadetblue;
  }#meet-container{
    background-color: brown;
  }

#svg-container{
  background-color: white;
  height: 100px;
  width: 100%;
}
</style>