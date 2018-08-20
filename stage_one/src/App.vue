<template>
  <div id="app">
    <vue-header></vue-header>
    <img src="./assets/logo.png">
    <router-view></router-view>
    <vue-footer></vue-footer>
  </div>
</template>

<script>
import VueHeader from './components/Header';
import VueFooter from './components/Footer';
export default {
  name: 'App',
  components: {
        VueHeader, VueFooter
  },
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
