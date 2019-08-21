<template>
  <div id="app">
    <compHeader></compHeader>

      <div>
        <compFeatured></compFeatured>
        <compMenu></compMenu>
        <compCallUs></compCallUs>
        <compNewsletter></compNewsletter>
      </div>

    <compFooter></compFooter>
  </div>
</template>

<script>
import compHeader from './components/Header_footer/Header.vue'
import compFooter from './components/Header_footer/Footer.vue'
import compFeatured from './components/Featured/index.vue'
import compMenu from './components/Menu/index.vue'
import compCallUs from './components/CallUs/index.vue'
import compNewsletter from './components/Newsletter/index.vue'

export default {
  name: 'app',
  components: {
    compHeader,
    compFooter,
    compFeatured,
    compMenu,
    compCallUs,
    compNewsletter
  }
};
</script>

<style>

@import './assets/style.css';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
