<template>
  <div id="app">
    <BaseHeader/>
    <BaseFooter />
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseFooter from './components/BaseFooter.vue';

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseFooter,
  }
}
</script>

<style lang="scss">
  @import './assets/style/global.scss';
</style>
