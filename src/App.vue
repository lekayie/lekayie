<template>
  <div id="app">
    <!-- <Timeline msg="Hello vue in Linux Mint" /> -->
    <h3>
      Hello Linux Mint
    </h3>
  </div>
</template>

<script>
//import Timeline from "./components/Timeline";

export default {
  name: "App",
  components: {
    Timeline
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>