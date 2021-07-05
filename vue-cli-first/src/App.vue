<template>
  <div id="app">
    
    <img class="foto" src="./assets/domo.webp" alt="Domodossola">
     <!-- <HelloWorld msg="Welcome to Your Vue.js App"/>  -->
    <Title/>
    <Hero/>
  </div>
</template>

<script>
//  import HelloWorld from './components/HelloWorld.vue'
 import Title from './components/Title.vue';
 import Hero from './components/Hero.vue';

export default {
  name: 'App',
  components : {
    Title,
    Hero
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
