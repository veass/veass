<template>
  <div class="nav-bar">
    <nav>
      <ul>
        <li>
          <p>
            {{ item1 }}
          </p>
        </li>
      </ul>
    </nav>
  </div>
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
  created(){
   console.log('xer');
   axios.get('https://veasweb.ru/wp-json')
   .then(response => {
     this.item1 = response.data.name;
    // console.log(response.data.name)
   })
  }
}
</script>

<style lang="sass" scoped>
  p
    color: white
  a
    text-decoration: none
  .nav-bar
    position: fixed
    height: 63px
    width: 100%
    background-color: #21201F
    z-index: 100
</style>