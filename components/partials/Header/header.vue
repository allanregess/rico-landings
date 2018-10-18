<template>
  <section class="header">
    <div class="group">
      <img 
        class="logo" 
        src="https://picsum.photos/100/30">
      <a href="#">CADASTRAR-SE</a>
    </div>  
  </section>
</template>

<script>

</script>

<style lang="stylus" scoped>
@import '~assets/stylesheets/variables.styl'

.header
  width: 100%
  height: 50px
  background: $black

  .group
    display: grid
    grid-template-columns: 20px 1fr 20px


</style>
