
<script>
export default {
  name:'reviews'
}
</script>

<template>
  <div id="main-wrapper">
    <div id="main-container">
      <!-- CONTENITORE DEL TITOLO DI SEZIONE -->
      <div id="container">
        <div id="what"><span>WHAT PEOPLE SAY</span></div>
        <div id="title"><h2>Reviews</h2></div>
      </div>
      <!-- CONTENITORE DELLE CARDS -->
      <div id="reviews-box">
        <!-- CARD -->
        <div class="card">
          <div class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eos possimus amet modi optio sapiente distinctio, quasi tempora nam! Voluptates, quo! Amet aliquam numquam, ipsam accusamus dolore alias ipsum voluptatibus commodi.</div>
          <div class="card-img">Immagine</div>
          <div class="card-name"><span>15$</span></div>
        </div>

                <!-- CARD -->
                <div class="card">
          <div class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eos possimus amet modi optio sapiente distinctio, quasi tempora nam! Voluptates, quo! Amet aliquam numquam, ipsam accusamus dolore alias ipsum voluptatibus commodi.</div>
          <div class="card-img">Immagine</div>
          <div class="card-name"><span>15$</span></div>
        </div>

                <!-- CARD -->
        <div class="card">
          <div class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eos possimus amet modi optio sapiente distinctio, quasi tempora nam! Voluptates, quo! Amet aliquam numquam, ipsam accusamus dolore alias ipsum voluptatibus commodi.</div>
          <div class="card-img">Immagine</div>
          <div class="card-name"><span>15$</span></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    background-color: cornflowerblue;
    width: 100%;
    display: flex;
    justify-content: center;
  }#main-container{
    margin-top:400px ;
    background-color: bisque;
    width: 80%;
  }#container{
    display: flex;
    flex-direction:column ;
    justify-content: center;
    align-items: center;
  }

  #reviews-box{
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
</style>