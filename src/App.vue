<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      // title: "La mia prima app Vite",
    };
  },

  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <header>
    <app-title />
  </header>

  <main>
    <app-hero />
  </main>
</template>

<style></style>
