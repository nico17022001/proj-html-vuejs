
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
          <div class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi mollis eleifend ante ut sagittis. Sed sodales, urna et imperdiet placerat, ex nisi aliquam orci, ac varius odio libero et arcu.</div>
          <div class="card-img"><img src="../../assets/img/img-main/ragazzo1.jpg"></div>
          <div class="card-name"><span><strong>John Doe</strong></span></div>
        </div>

                <!-- CARD -->
                <div class="card">
          <div class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi mollis eleifend ante ut sagittis. Sed sodales, urna et imperdiet placerat, ex nisi aliquam orci, ac varius odio libero et arcu.</div>
          <div class="card-img"><img src="../../assets/img/img-main/ragazzo2.jpg"></div>
          <div class="card-name"><span><strong>Pete Jones</strong></span></div>
        </div>

                <!-- CARD -->
        <div class="card">
          <div class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi mollis eleifend ante ut sagittis. Sed sodales, urna et imperdiet placerat, ex nisi aliquam orci, ac varius odio libero et arcu.</div>
          <div class="card-img"><img src="../../assets/img/img-main/ragazzo3.jpg"></div>
          <div class="card-name"><span><strong>Mark Wilson</strong></span></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    width: 100%;
    display: flex;  
    justify-content: center;
  }#main-container{
    margin-top:400px ;
    width: 80%;
  }#container{
    display: flex;
    flex-direction:column ;
    justify-content: center;
    align-items: center;
  }#what{
    color: #be9359;
  }#title{
    color: #b0b0b0;
    font-size: xxx-large;
  }

  #reviews-box{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 30px;
  }.card{
    width: calc(100% / 3);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }.card-text{
    text-align: center;
    font-size: large;
    padding: 0px 74px;
    margin-bottom: 20px;
  }.card-img{
    width: 86px;    
  }img{
    width: 100%;
    border-radius: 50%;
  }.card-text{
    color: gray;
  }.card-name{
    margin-top: 10px;
    color: #be9359;
    font-style: italic;
  }
</style>