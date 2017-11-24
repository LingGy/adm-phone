<template>
  <div id="app">
    <v-header></v-header>
    <div class="tab">
      <div class="tav-item">
        <router-link to="/a1"></router-link>
      </div>
      <div class="tav-item">
        <router-link to="/a2"></router-link>
      </div>
      <div class="tav-item">
        <router-link to="/a3"></router-link>
      </div>
    </div>
  </div>
</template>

<script>
import header from './components/header/header.vue';
export default {
  'v-header': header
};
</script>

<style lang='scss'>

</style>
