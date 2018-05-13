<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
  </div>
</template>

<script>
import HomeHeader from './compintents/Header'
import HomeSwiper from './compintents/Swiper'
export default {
  components: {
    HomeSwiper,
    HomeHeader},
  name: 'Home'
}
</script>

<style>
</style>
