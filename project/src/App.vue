<template>
  <div id="app">
    <myadd></myadd>
    <mysub></mysub>
  </div>
</template>

<script>
import Add from "./views/Add.vue";
import Sub from "./views/Sub.vue";
export default {
  components: {
    myadd: Add,
    mysub: Sub,
  },
};
</script>

<style>
</style>
