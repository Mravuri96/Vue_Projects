<template>
  <section>
    <input v-model="msg" v-on:input="reverse" placeholder="Enter text here ..."/>
    <h1>{{ reverse }}</h1>
  </section>
</template>

<script>
export default {
  name: "TextReverse",
  data: function () {
    return {
      msg: "",
    };
  },
  computed: {
    reverse: function () {
      return this.msg.split("").reverse().join("");
    },
  },
};
</script>

<style lang="css" scoped>
input {
  width: 300px;
  padding: 16px;
  margin: 16px;
  font-size: 1.5rem;
}
</style>

