<template>
  <div id="app">
    <Navigation></Navigation>
    <Themeground></Themeground>
    <Carousel></Carousel>
  </div>
</template>

<script>
  import Navigation from './components/navigation/Navigation.vue'
  import Themeground from './components/home/Themeground.vue'
  import Carousel from './components/home/Carousel.vue'

  export default {
    name: 'app',
    components: {
      Navigation,
      Themeground,
      Carousel
    }
  }
</script>

<style>
  /* #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  } */
</style>
