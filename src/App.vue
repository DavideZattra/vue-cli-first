<template>
  <div id="app">
    <Header />
    <Jumbotron />
  </div>
</template>

<script>
import Header from './components/header'
import Jumbotron from './components/jumbotron.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron
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
