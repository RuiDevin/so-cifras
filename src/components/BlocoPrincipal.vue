<script>
import NovoBloco from "./NovoBloco.vue";
export default {
  components: { NovoBloco },
  data() {
    return {
      imagens: new URL(
        "./assets/Fotos_Jogadores/Cristiano-Ronaldo.png",
        import.meta.url
      ).href,
    };
  },
};
</script>

<template>
  <main id="content">
  </main>
</template>

<style></style>
