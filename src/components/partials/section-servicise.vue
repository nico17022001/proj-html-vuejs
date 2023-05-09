
<script>
export default {
  name:'servicise'
}
</script>

<template>
  <div id="main-wrapper">
    <!-- CONTENITORE DEL PRIMO TESTO  -->
    <div id="text-container">
      <div id="mens-container">
        <span>MEANS GROOMING</span>
      </div>
      <div id="service-container">
        <h3>SERVICISE</h3>
      </div>
    </div>

    <!-- CONTENITORE TESTO ED IMMAGINI -->
    <div id="service-box">
      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-txt">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus </div>
      </div>
      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-txt">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus </div>
      </div>
      <!-- CARD -->
      <div class="card">
        <div class="card-svg">SVG</div>
        <div class="card-title">Titolo card</div>
        <div class="card-txt">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus </div>
      </div>
    </div>
    
    <!-- CONTENITORE READ -->
    <div id="read-container">
      <div id="read-about">READ ABOUT OUR SERVICES</div>
    </div>

    <!-- CONTENITORE SVG -->
    <div id="svg-container">SVG</div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    height: 500px;
    background-color:blueviolet ;
  }#text-container{
    background-color: blanchedalmond;
    height: 100px;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }#mens-container{
    background-color: cadetblue;
  }#service-container{
    background-color: chocolate;
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
  }#read-about{
    height: 100%;
    background-color: aqua;
    display: flex;
    align-items: center;
  }

  #svg-container{
    height: 100px;
    background-color: chartreuse;
  }
</style>