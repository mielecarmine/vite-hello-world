<script>
import AppTitle from "./components/AppTitle.vue";
import AppJumbo from "./components/AppJumbo.vue";

export default {
  components: {
    AppTitle: AppTitle,
    AppJumbo: AppJumbo,
  },
};
</script>

<template>
  <AppJumbo>
    <AppTitle></AppTitle>
  </AppJumbo>
</template>

<style scoped></style>
