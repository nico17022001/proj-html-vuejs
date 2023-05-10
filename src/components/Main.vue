<script>
import barberShop from './partials/section-Barber-shop.vue'
import proBarbers from  './partials/section-pro-barbers.vue'
import servicise from './partials/section-servicise.vue'
import avada from './partials/section-avada.vue'
import reviews from './partials/section-reviews.vue'
import blog from  './partials/section-blog.vue'

export default {
  name:'Main',
  

  components:{
    barberShop,
    proBarbers,
    servicise,
    avada,
    reviews,
    blog,
  }
}
</script>

<template>
  <div id="main-wrapper">
    <div id="square-container">
      <div class="square">
        <div class="svg">
          <div>
          <i class="fa-solid fa-image disappear"></i>
          <i class="fa-solid fa-image appear"></i>
          </div>
          <div class="svg-name">Prebuilts</div>
        </div>
      </div>
      <div class="square">
        <div class="svg">
          <div>
            <i class="fa-solid fa-cart-shopping disappear"></i>
            <i class="fa-solid fa-cart-shopping appear"></i>
          </div>
          <div class="svg-name">Buy Now</div>
        </div>
      </div>
    </div>
    <barberShop/>
    <proBarbers/>
    <servicise/>
    <avada/>
    <reviews/>
    <blog/>
  </div>
</template>

<style lang="scss" scoped>
  #main-wrapper{
    position: relative;
  }#square-container{
    width: 66px;
    height: 200px;
    position: fixed;
    right: 12px;
    top: 160px;
    z-index: 10;    
  }.square{
    background-color: white;
    width: 100%;
    height: 66px;
    margin-bottom: 10px;
    border-radius:6px ;
    overflow: hidden;
    color: #33475b;
    cursor: pointer;
    
    
  }.svg{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    position: relative;
  }i{
    font-size: x-large;
  }.appear{
    position: absolute;
    right: -29px;
  }.svg-name{
    font-size: small;
    margin-top: 4px;
  }

  

  .square:hover{
    .disappear{
      position: absolute;
      left: -29px;
      animation: moveLeft .2s linear;
    }

    .appear{
      left: 21px;
      top: 11px;
      animation: moveRight .2s linear;
    }

    .svg-name{
      position: absolute;
      bottom: 10.6px;
    }
  }

  @keyframes moveLeft{
    0% {
    left: 21px;
    top: 11px
    }
    50% {
      left: -20px;
      top: 11px
    }
    100% {
      left: -29px;
      top: 11px
    }
  }

  @keyframes moveRight{
    0% {
      left: 80px;
      top: 11px;
    }
    50% {
      left: 50px;
      top: 11px;
    }
    100% {
      left: 21px;
      top: 11px;
    }
  }
</style>