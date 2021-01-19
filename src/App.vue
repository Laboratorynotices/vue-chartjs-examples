<template>
  <div id="app">
    <h1>Примеры работы с vue-chartjs</h1>
    <h2>Первый график</h2>
    <Chart class="w-75" />
  </div>
</template>

<script>
import Chart from './components/Chart.vue'

export default {
  name: 'App',
  components: {
    Chart
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
.w-75 {
  width: 75%;
  margin-left: auto;
  margin-right: auto;
}
</style>
