<template>
  <div id="app">
    <Header/>
    <Portfolio/>
  </div>
</template>

<script>
import Portfolio from "./components/Portfolio";
import Header from "./components/Header";

export default {
  name: "App",
  components: {
    Portfolio,
    Header
  }
};
</script>

<style>
/* #app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
