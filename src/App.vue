<template>
  <HeaderIndex/>
  <BannerTraders/>
  <ContentCards/>
  <BannerLeading/>
  <ComunyTraders/>
  <FooterIndex/>
</template>

<script>
import HeaderIndex from './components/header/HeaderIndex.vue'
import BannerTraders from './components/content/BannerTraders.vue'
import ContentCards from './components/content/ContentCards.vue'
import BannerLeading from './components/content/BannerLeading.vue'
import ComunyTraders from './components/content/ComunyTraders.vue'
import FooterIndex from './components/footer/FooterIndex.vue'

export default {
  name: 'App',
  components: {
    HeaderIndex,
    BannerTraders,
    ContentCards,
    BannerLeading,
    ComunyTraders,
    FooterIndex
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
