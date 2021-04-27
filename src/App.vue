<template>
<img src="./assets/boba-drink.png" alt="boba drink">
  <Main msg="Boba Friends App"/>

</template>

<script>
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Main
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


img {
  width: 10%;
  height: auto;
}
</style>
