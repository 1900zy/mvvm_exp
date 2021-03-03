<template>
  <div id="mvvm-app">
    <input v-model="title" />
    <h2>{{ title }}</h2>
  </div>
</template>

<script>
export default {
  name: "mvvm-app",
  data() {
    return {
      title: "hello world",
    };
  },
  methods: {},
};
</script>

<style>
</style>
