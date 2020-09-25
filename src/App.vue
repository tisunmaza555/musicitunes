<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logomusic11.png" width="50%" height="auto">
    <itune/>
  </div>
</template>

<script>
import itune from './components/itune'

export default {
  name: 'App',
  components: {
    itune,
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
