<template>

  <RNG msg = "Welcome to Unit Testing"/>
</template>

<script>
import RNG from "./components/RNG.vue";

export default {
  name: "App",
  components: {
    RNG,
  },
};
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
