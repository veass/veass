<template>
  <div id="app">
    <nav-bar />
    <router-view />
    <main-footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar'
import MainFooter from './components/Footer'
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

Vue.use(BootstrapVue)
Vue.use(IconsPlugin)

export default {
  name: 'App',
  components: {
    NavBar,
    MainFooter,

  }
}
</script>

<style lang="sass">
#app 
  font-family: Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50

body
  line-height: 1 //переписать

</style>
