<script>
export default {
  name: "AppCard",
};
</script>

<template>
  <div class="card">
    <img
      src="https://images.amcnetworks.com/amc.com/wp-content/uploads/2015/04/cast_bb_700x1000_walter-white-lg.jpg"
      alt="ww"
    />
    <h3>WALTER WHITE</h3>
    <div>Breaking Bad</div>
    <div>Presumed dead</div>
  </div>
</template>

<style scoped>
img {
  max-width: 100%;
  width: 200px;
  padding: 10px;
}

.card {
  background-color: #2e3a46;
  text-align: center;
  color: white;
}
</style>
