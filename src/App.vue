<template>
  <div id="app">
    <nav-bar />
    <core />
    <technology />
    <portfolio />
    <main-footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar'
import MainFooter from './components/Footer'
import Core from './components/Core'
import Technology from './components/Technology'
import Portfolio from './components/Portfolio'

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
    Core,
    Technology,
    Portfolio

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



</style>
