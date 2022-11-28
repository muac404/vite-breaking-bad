<script>
export default {
  name: "AppCard",
  props: {
    info: Object,
  },
};
</script>

<template>
  <div class="card">
    <img :src="info.img" alt="info.name" />
    <h3>{{ info.name }}</h3>
    <div>{{ info.category }}</div>
    <div class="status">
      <em> {{ info.status }} </em>
    </div>
  </div>
</template>

<style scoped>
img {
  width: 160px;
  padding: 10px;
}

.card {
  background-color: #2e3a46;

  width: 200px;
  margin: 10px;
  padding: 5px;
  text-align: center;
  color: white;
}

.status {
  color: lightblue;
}
</style>
