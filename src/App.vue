<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <MainHeader/>
    <MainHero/>
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainHero from './components/MainHero.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    MainHero,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }
  
</style>
