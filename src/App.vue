<template>
  <div id="app">
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from './components/header'
import Hero from './components/hero'

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  height: 100vh;
  width: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-image: url("assets/main-background.jpg");
  background-position: center;
  background-size: cover;
}
</style>
