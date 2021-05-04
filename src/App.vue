<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld message="Welcome to Your Vue.js App" />
    <br />
    <Message message="This page was made with vue.js"></Message>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Message from "./components/DynamicallyBoundMessage";

export default {
  name: "App",
  components: {
    HelloWorld,
    Message,
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
