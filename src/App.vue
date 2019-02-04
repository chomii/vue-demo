<template>
  <div id="app">
    <the-nav-bar/>
    <the-hero-section/>
  </div>
</template>

<script>
import theNavBar from './components/theNavBar.vue';
import theHeroSection from './components/theHeroSection.vue';
export default {
  name: 'app',
  components: {
    theNavBar,
    theHeroSection
  }
}
</script>

<style>

</style>
