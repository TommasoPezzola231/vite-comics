<script setup>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<template>
  <AppHeader />

  <div class="jumbotron"></div>

  <AppMain />

  <AppFooter />
</template>

<style scoped>
.jumbotron {
  width: 100vw;
  max-width: 100%;
  height: 400px;
  background-image: url(./assets/jumbotron.jpg);
  background-size: cover;
}
</style>
