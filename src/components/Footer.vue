<template>
  <footer class="main-footer">
    <div class="mainblock" />
  </footer>
</template>

<script>
export default {
  name: 'MainFooter',
 
  }
</script>

<style lang="sass" scoped>

@mixin flexrow
  display: flex
  flex-direction: row
.main-footer
  height: auto
  background-color: #404040
  width: 100%
  .mainblock
    margin-left: auto
    margin-right: auto
    width: auto
    display: flex
    flex-direction: row
    padding: 30px 0px 0px 30px
    justify-content: center
    height: auto
    flex-wrap: wrap
</style>