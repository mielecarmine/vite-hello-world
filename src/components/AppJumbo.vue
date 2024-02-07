<script>
import AppTitle from "./AppTitle.vue";

export default {
  components: {
    AppTitle: AppTitle,
  },
};
</script>

<template>
  <div class="jumbo">
    <AppTitle></AppTitle>
  </div>
</template>

<style scoped>
.jumbo {
  height: 100px;
  display: flex;
  justify-content: center;
  background-color: rgb(99, 99, 99);
}
</style>
