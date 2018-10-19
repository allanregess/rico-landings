<template>
  <section class="header">
    <div class="group">
      <img 
        class="logo" 
        src="https//picsum.photos/100/30">
      <a 
        class="btn" 
        href="#">CADASTRAR-SE</a>
   
    </div>  
  </section>
</template>

<script>

</script>

<style lang="stylus" scoped>
@import '~assets/stylesheets/variables.styl'

.header
  width 100%
  background $red

  .group
    display grid
    grid-template-columns 20px 100px 1fr 150px 20px
    grid-template-rows 50px
    align-items center
    grid-template-areas ". logo . button ."

    .logo
      grid-column 2
      justify-self center
      grid-area logo
    
    .btn
      grid-column 2
      justify-self center
      grid-area button
      text-decoration none

</style>
