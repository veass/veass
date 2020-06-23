<template>
  <section id="main-core">
    <div class="main-core-content">
      <div class="flexable-content">
        <div class="flexable-content-text">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
        </div>
        <div class="flexable-content-button">
          <b-button squared variant="outline-primary" href="#">
            Button
          </b-button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>


export default {
  name: 'MainCore',
  
}
</script>

<style lang="sass">
@import "styles.sass"
#main-core 
  width: 100%
  height: 100vh
  background-color: yellow
  .main-core-content 
    @include contain
    .flexable-content 
      @include coloumncenter
      height: inherit 
      .flexable-content-text 
        @include center
        p
          width: 400px
          font-size: 30px
    
    // font-weight: 700
    // padding: 1.375rem 5.75rem
    // font-size: 16px

</style>