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
body {
  height: 100vh;
  display: grid;
  place-items: center;
}
#app {
  background-color: whitesmoke;
  display: flex;
  flex-direction: column;
  place-items: center;
  justify-content: center;
  align-content: center;
  width: 500px;
  position: relative;
  box-shadow: 0px 0px 15px 0px rgba(0, 0, 0, 0.3);
}
</style>

