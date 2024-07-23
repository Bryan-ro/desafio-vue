<template>
  <div id="app">
    <Header></Header>
    <hero></hero>
    <main id="main">
      <!-- Aqui você deve usar tags explícitas para seus componentes -->
      <!-- <sobre></sobre> -->
      <!-- <skills></skills> -->
      <!-- <resume></resume>
      <portfolio></portfolio> -->
    </main>
    <footer id="footer">
      <div class="container">
        <div class="copyright">
          &copy; Copyright. <strong><span> Portfolio Feriani Store </span></strong>
        </div>
        <div class="creditos">
          Desenvolvido por <i class="bi bi-github"></i><a href="https://github.com/guuhferiani" target="_blank"> Feriani </a>
        </div>
      </div>
    </footer>
    <a href="#" class="back-to-top d-flex align-items-center justify-content-center">
      <i class="bi bi-arrow-up-short"></i>
    </a>
  </div>
</template>

<script>
import Header from "./header.vue";
import hero from "./hero.vue";
// import sobre from "./sobre.vue"; // Certifique-se de importar todos os componentes necessários
// import skills from "./skills.vue";
// import resume from "./resume.vue";
// import portfolio from "./portfolio.vue";

export default {
  components: {
    Header,
    hero,
    // sobre,
    // skills,
    // resume,
    // portfolio,
  },
};
</script>

<style scoped>
/* Adicione qualquer estilo específico ao App.vue aqui */
</style>
