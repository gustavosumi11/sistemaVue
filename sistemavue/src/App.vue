<template>
  <div id="app">
  <HeaderPage/>
<CarouselPage/>
  <router-view/>
  </div>
</template>

<script>


import HeaderPage from './components/Header/HeaderPage.vue';
import CarouselPage from './components/Carousel/CarouselPage.vue'




export default {
  name: 'App',
  components: {
    HeaderPage,
    CarouselPage,
  
   
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
* {
  margin: 0px;
  padding: 0px;
  background-color: #F5F5F5;
}
</style>
