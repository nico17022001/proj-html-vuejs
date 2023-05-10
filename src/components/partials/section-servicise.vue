
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
        <span>MENS GROOMING</span>
      </div>
      <div id="service-container">
        <h2>Services</h2>
      </div>
    </div>

    <!-- CONTENITORE TESTO ED IMMAGINI -->
    <div id="service-box">
      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/macchinetta.png" alt=""></div>
        <div class="card-title"><strong>Trim & Cut</strong></div>
        <div class="card-txt">
          <span>
            Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.
          </span>
        </div>
      </div>
      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/prodotto.png" alt=""></div>
        <div class="card-title"><strong>Wash & Dry</strong></div>
        <div class="card-txt">
          <span>
            Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashion.
          </span>
        </div>
      </div>
      <!-- CARD -->
      <div class="card">
        <div class="card-svg"><img src="../../assets/img/img-main/rasoio.png" alt=""></div>
        <div class="card-title"><strong>Beard Tidy</strong></div>
        <div class="card-txt">
          <span>
            Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.
          </span>
        </div>
      </div>
    </div>
    
    <!-- CONTENITORE READ -->
    <div id="read-container">
      <div id="read-about">READ ABOUT OUR SERVICES</div>
    </div>

    <!-- CONTENITORE SVG -->
    <div id="svg-container">
      <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:black;padding:0;"><path d="M0 100 L50 2 L100 100 Z"></path></svg>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    background-color: white;
  }#text-container{
    height: 100px;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 40px;
  }#mens-container{
    color: #be9359;
    font-size: large;
  }#service-container{
    font-size: xxx-large;
    color: #b0b0b0;
  }

  #service-box{
    width: 100%;
    display: flex;
    justify-content: center;
    padding: 0px 200px;
    margin-top: 70px;
  }.card{
    width: calc(100% / 3);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }.card-svg img{
    width: 85px;
    height: 130px;
  }.card-title{
    color: #be9359;
    font-size: xx-large;
    margin-top: 25px;
  }.card-txt{
    color: #b0b0b0;
    text-align: center;
    font-size: x-large;
    padding: 0px 51px;
    margin-top: 20px;
  }

  #read-container{
    display: flex;
    justify-content: center;
    margin: 50px 0px;
  }#read-about{
    border: solid 2px #be9359;
    color: #be9359;
    display: flex;
    align-items: center;
    padding: 20px 50px;
    margin-bottom: 90px;
  }

  #svg-container{
    height: 100px;
    width: 100%;
  }
</style>