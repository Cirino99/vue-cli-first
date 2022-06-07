<template>
  <div id="app">
    <Hero/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <NuovoComponente/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import HelloWorld from './components/HelloWorld.vue'
import NuovoComponente from './components/NuovoComponente.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NuovoComponente,
    Hero
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
</style>
