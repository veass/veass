<template>
  <section id="technology">
    <div class="fixable-technology">
      <div class="fixable-technology-content" />
    </div>
  </section>
</template>

<script>
export default {
  name: 'Technology',
 
  }
</script>

<style lang="sass" scoped>
@import "styles.sass"
#technology 
  .fixable-technology
    @include contain
    .fixable-technology-content
     height: 600px
      
</style>