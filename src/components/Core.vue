<template>
  <div class="main-core" /> 
</template>

<script>

export default {
  name: 'MainCore',
  components: {
  }
}
</script>

<style lang="sass" scoped>
@mixin middle
  margin-left: auto
  margin-right: auto
@mixin row
  display: flex
  flex-direction: row
.main-core
  width: 100%
  height: 600px

</style>