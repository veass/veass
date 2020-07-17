<template>
  <header class="nav-bar">
    <div>
      <b-navbar type="dark">
        <b-navbar-brand href="#">
          Veass
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse" />

        <b-collapse
          id="nav-collapse"
          is-nav
        >
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="#" disabled>
              Technology
            </b-nav-item>
            <b-nav-item href="#" disabled>
              Portfolio
            </b-nav-item>
            <b-nav-item href="#" disabled>
              something3
            </b-nav-item>
            <b-nav-item href="#" disabled>
              something4
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </header>
</template> 

<script>

import axios from 'axios'

export default {
  name: 'NavBar',
  data(){
    return {
      item1: 'hello'
    }
  },
  // created(){
  // console.log('xer');
  //  axios.get('https://veasweb.ru/wp-json')
  //  .then(response => {
  //    this.item1 = response.data.name;
  //   // console.log(response.data.name)
  //  })
  // }
}
</script>

<style lang="sass" scoped>
  p
    color: white
  a
    text-decoration: none
  .nav-bar
    position: fixed
    width: 100%
    background-color: #21201F
    z-index: 100
</style>