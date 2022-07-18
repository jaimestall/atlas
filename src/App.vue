<template>
  <Navbar />
  <router-view />
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

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap");
* {
  font-family: "Open Sans", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
a {
  text-decoration: none;
}
::-webkit-scrollbar { 
display: none; 
}
.titulo-corpo {
  border-bottom: 1px solid #777;
  color: #777;
  font-size: 2em;
  line-height: 1;
  text-align: center;
  max-width: 1100px;
  margin: 0 auto;
  padding: 20px 0;
}
.cards-box {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
.card {
  background-color: #f0f0f0;
  flex: 1 1 360px;
  margin: 15px;
  padding: 10px 0;
  border: 1px solid #777;
  box-shadow: 1.5px 1.5px 0 #bbb;
}
.card h2 {
  font-size: 1.75em;
  color: #a4a4a4;
  margin: 0 20px 5px 20px;
  padding-bottom: 10px;
  border-bottom: 3px solid white;
}
.card p {
  font-size: 1em;
  padding: 0 20px;
  line-height: 1.8;
  color: #7c7c7c;
}
.card ul {
  font-size: 1em;
  padding: 0 20px;
  line-height: 1.8;
  color: #7c7c7c;
}
.card-itens {
  margin: 5px 15px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(15%, auto));
}
.card-item {
  border: 1px solid #777;
  align-items: left;
  text-align: center;
  margin: 5px;
  padding: 10px 0;
}
.code-bold {
  color: white;
  font-weight: bold;
  font-family: monospace;
  background-color: #777;
  padding: 1px 5px;
  border-radius: 5px;
}
</style>
