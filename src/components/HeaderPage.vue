<template>
  <div class="container">
    <img class="logo" alt="Leon logo" src="../assets/images/logo.png" />
    <nav class="links">
      <button class="buger-button" @click="toggleMenu = !toggleMenu">
        <span></span><span></span><span></span>
      </button>
      <ul v-show="toggleMenu">
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      toggleMenu: false,
    };
  },
};
</script>
