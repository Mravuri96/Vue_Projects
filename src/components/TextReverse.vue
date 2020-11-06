<template>
  <section>
    <input v-model="msg" v-on:input="reverse" />
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

