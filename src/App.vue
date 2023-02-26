<template>
  <div>
    <Button
      class="p-button-secondary"
      label="Submit"
      @click="handleClick($event)"
    />
  </div>
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";

import Button from "primevue/button";

export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    Button: Button,
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
