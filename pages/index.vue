<template>
  <section class="main">
    <Header />
    <Content />
    <Footer />
  </section>  

</template>

<script>
import Header from '~/components/partials/Header/header.vue'
import Footer from '~/components/partials/Footer/footer.vue'
import Content from '~/components/partials/Content/content.vue'

export default {
  components: {
    Header,
    Footer,
    Content
  }
}
</script>

<style lang="stylus" scoped>

</style>
