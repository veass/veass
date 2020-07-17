<template>
  <section id="technology">
    <div class="fixable-technology">
      <div class="fixable-technology-content">
        <histogramm />
      </div>
    </div>
  </section>
</template>

<script>
import Histogramm from './child/histogramm'
export default {
  name: 'Technology', 
  components: {
    Histogramm
  },
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