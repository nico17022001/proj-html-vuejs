<script>
import barberShop from './partials/section-Barber-shop.vue'
import proBarbers from  './partials/section-pro-barbers.vue'

export default {
  name:'Main',
  

  components:{
    barberShop,
    proBarbers,
  }
}
</script>

<template>
  <barberShop/>
  <proBarbers/>
</template>

<style lang="scss" scoped>

</style>