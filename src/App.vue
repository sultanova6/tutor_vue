<template>
  <div id="app">
      <p>Hello</p>
      <v-main-wrapper></v-main-wrapper>
  </div>
</template>

<script>
  import vMainWrapper from './components/v-main-wrapper'

export default {
  name: 'App',
  components: {
    vMainWrapper
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');
#app {
  font-family: Nunito, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
