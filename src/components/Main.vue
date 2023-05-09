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
  <barberShop/>
  <proBarbers/>
  <servicise/>
  <avada/>
  <reviews/>
  <blog/>
</template>

<style lang="scss" scoped>

</style>