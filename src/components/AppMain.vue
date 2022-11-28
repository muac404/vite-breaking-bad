<script>
import AppCard from "./AppCard.vue";
export default {
  name: "AppMain",
  components: {
    AppCard,
  },
};
</script>

<template>
  <section class="container">
    <select name="" id="">
      <option selected>Select category</option>
      <option value="">Opt 1</option>
    </select>
    <div class="container-cards">
      <div class="row">
        <div class="col">
          <AppCard />
        </div>
        <div class="col">
          <AppCard />
        </div>
      </div>
    </div>
  </section>
</template>

<style>
select {
  padding: 10px;
}

.container {
  max-width: 1000px;
  margin: auto;
}

.container-cards {
  background-color: white;
  margin: auto;
  max-width: 1000px;
}

.row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 20px;
}
.col {
  margin: 10px;
}
</style>
