<template>
    <div class="app">
      <Navbar />
      <Jumbotron />
    </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
  }
};
</script>

<style>
#app{
  font-family:Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing:grayscale;
}
  
</style>
