<script setup>
import Cards from "./components/Cards.vue";
</script>

<template>
  <header><v-img src="assets/"></v-img></header>
  <main>
    <h1>Gerador de paleta de cores</h1>
    <Cards />
  </main>
  <footer>
    <span>&copy;Todos os direitos reservados - 2025</span>
  </footer>
</template>

<style scoped lang="scss">
header {
  width: 100%;
  padding: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
}

main {
  width: 100%;
  padding: 24px;

  h1 {
    color: #69247c;
    font-size: 40px;
    text-align: center;
  }
}
</style>
