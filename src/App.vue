<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <EjercicioColor/>
  </div>
</template>

<script>
import EjercicioColor from './components/EjercicioColor.vue'
// import EjercicioUno from './components/EjercicioUno.vue'


export default {
  name: 'App',
  components: {
    EjercicioColor
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
  margin-top: 60px;
}
</style>
