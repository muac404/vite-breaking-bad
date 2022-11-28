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
      <div class="founds">
        <h4>Found 62 characters</h4>
      </div>
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
  padding: 5px 20px;
  margin-bottom: 10px;
  border-radius: 5px;
  border: none;
}

.container {
  max-width: 1000px;
  margin: auto;
}

.container-cards {
  background-color: white;
  margin: auto;
  padding: 10px;
  max-width: 1000px;
}

.founds {
  max-width: 900px;
  padding: 10px;
  margin: auto;
  background-color: #2e3a46;
  color: white;
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
