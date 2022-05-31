<script setup>
import HeaderPage from "./components/HeaderPage.vue";
import MainLeon from "./components/MainLeon.vue";
import FooterPage from "./components/FooterPage.vue";
</script>

<template>
  <header>
    <HeaderPage />
  </header>

  <main>
    <MainLeon />
  </main>

  <footer>
    <FooterPage />
  </footer>
</template>

<style>
@import "./assets/css/main.css";
@import url("./assets/css/all.min.css");
</style>
