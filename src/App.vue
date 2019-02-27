<template>
  <div id="app">
      <the-navbar></the-navbar>
      <router-view/>
  </div>
</template>

<script>
import TheNavbar from './components/TheNavbar';

export default {
  name: 'App',
  metaInfo: {},
  components: { TheNavbar },
};
</script>

<style lang="scss">
</style>
