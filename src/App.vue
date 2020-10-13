<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import { defineAsyncComponent } from "vue";
export default {
  name: "App",
  components: {
    HelloWorld: defineAsyncComponent(() =>
      import("./components/HelloWorld.vue")
    ),
  },
  setup() {
    console.log(111);
  },
};
</script>

<style lang="less"></style>
