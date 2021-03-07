<template>
  <div id="app">
    <Header />
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> | -->
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />

    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->

    <HelloWorld msg="Hello World" />

    <Bottom />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Bottom from "./components/Bottom.vue";
// import Home from "./components/Home.vue";
// import About from "./components/About.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Header,
    Bottom,
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
