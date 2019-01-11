<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <li v-for="i in total" :key="i">
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </li>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  data() {
    return {
      total: 1000,
    };
  },
  name: 'app',
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
