<script>
import NovoBloco from "@/NovoBloco.vue";
export default {
  components: { NovoBloco },
  data() {
    return {
      professores: ["Eduardo", "Marco", "Ivo"],
    };
  },
};
</script>

<template>
  <main id="content">
    <NovoBloco titulo="Alunos" :nomes="['miguel', 'Ana']" />
    <NovoBloco titulo="Professores" :nomes="professores" />
    <NovoBloco class="alerta" />
    <NovoBloco class="alerta" />
  </main>
  
</template>
<style></style>