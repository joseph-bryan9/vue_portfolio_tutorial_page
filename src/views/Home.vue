<template>
  <div id="app">
    <Lander />
    <Portfolio />
  </div>
</template>

<script>
import Lander from "../components/lander";
import Portfolio from "../components/portfolio";

export default {
  name: "Home",
  components: {
    Lander,
    Portfolio,
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
  /* margin-top: 60px; */
}
</style>
