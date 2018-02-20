<template>
  <div id="app">
    <Header msg="Welcome to the TFL Planner App"/>
    <Status />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Status from './components/Status.vue'

export default {
  name: 'app',
  components: {
    Header,
    Status
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
