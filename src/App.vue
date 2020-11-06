<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <TextReverse />
  </div>
</template>

<script>
import TextReverse from "./components/TextReverse.vue";

export default {
  name: "App",
  components: {
    TextReverse,
  },
};
</script>
<style lang="css">
#app {
  text-align: center;
  display: grid;
  place-items: center;
}
</style>

