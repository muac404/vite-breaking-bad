<script>
import AppLogo from "./AppLogo.vue";

export default {
  name: "AppHeader",
  components: {
    AppLogo,
  },
};
</script>

<template>
  <section class="header">
    <AppLogo />
    <h1>Breaking Bad API</h1>
  </section>
</template>

<style scoped>
.header {
  height: 80px;
  display: flex;
}

h1 {
  color: white;
  margin-left: 10px;
}
</style>
