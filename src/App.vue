<template>
  <div id="app">
    <router-view></router-view>
    <FooterGuite v-show="$route.meta.showFooter"></FooterGuite>
  </div>
</template>

<script>
import FooterGuite from './components/FooterGuite/FooterGuite.vue'
export default {
  name: 'App',
  components: {
    FooterGuite
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .app
    width 100%
    height: 100%
    background: #f5f5f5
</style>
