<template>
  <div>
    <p>Home</p>
    <p class="accent">With SCSS!</p>
  </div>
</template>

<script>
export default {
  name: "Home",
  metaInfo: {
    title: "Vue Template",
    titleTemplate: null
  },
};
</script>

<style lang="scss">
.accent {
  background-color: $secondary-color;
}
</style>