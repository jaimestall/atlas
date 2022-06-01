<template>
  <Navbar />
  <router-view />
  <img src="../src/assets/logo.jpg" alt="" />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style></style>
