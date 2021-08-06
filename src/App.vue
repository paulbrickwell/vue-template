<template>
  <div id="app">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  metaInfo: {
    titleTemplate: "%s | Vue Template",
    meta: [
      { charset: "utf-8" },
      { name: "viewport", content: "width=device-width, initial-scale=1" },
    ],
  },
};
</script>
