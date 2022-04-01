<template>
  <div class="container">
    <Header />
    <HomeContent />
    <Footer />
  </div>
</template>

<script>
import HomeContent from '../../components/HomeContent/index.vue'
import Header from '../../components/Header/index.vue'
import Footer from '../../components/Footer/index.vue'

export default {
  components: {
    HomeContent,
    Header
  }
}
</script>

<style lang="sass" scoped>

</style>
