<template>
  <div id="app">
    <v-header></v-header>
    <v-swiper></v-swiper>
  </div>
</template>

<script>
import swiper from './components/swiper/swiper'
import header from './components/header/header'
export default {
  name: 'App',
  components: {
    'v-swiper': swiper,
    'v-header': header
  }
}
</script>
