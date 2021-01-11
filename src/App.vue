<template>
  <div id="app">
    <HeaderComponents/>
  </div>
</template>

<script>
import HeaderComponents from './common/HeaderComponents.vue'

export default {
  name: 'App',
  components: {
    HeaderComponents,
  },
}
</script>

<style>
 @import '../src/assets/style/style.css';
</style>
