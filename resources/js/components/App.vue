
<template>
  <div class="content">
    <AppHeader :title="title" />
    <main class="container mt-3">
      lista post
    </main>
  </div>
</template>

<script>
import AppHeader from "./AppHeader.vue";

export default {
  name: "App",
  data() {
    return {
      title: "Boolpress",
    };
  },
  components: {
    AppHeader,
  },
};
</script>

<style scoped>

</style>
