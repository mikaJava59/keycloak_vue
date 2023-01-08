<template>
  <div id="app">
    <NavVue/>
    <HomeComponent/>
  </div>
</template>

<script>
import HomeComponent from '@/components/HomeComponent.vue';
import NavVue from '@/components/NavVue.vue';

export default {
  name: 'App',
  components: {
    HomeComponent,
    NavVue,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
