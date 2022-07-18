<template>
  <div class="footer-bg">
    <div id="footer">
      <a href="https://github.com/jaimestall/atlas" target="_blank">GitHub</a>
      <a href="https://www.linkedin.com/in/jaimestall" target="_blank">LinkedIn</a>
    </div>
  </div>
</template>

<script>
// import XXX from './components/XXX.vue'

export default {
  components: {},
  data() {
    return {
      testeDado: "Confia.",
    };
  },
  mounted() {
    this.testeMethods();
  },
  methods: {
    testeMethods() {
      console.log("Vai dar tudo certo.");
    },
  },
};
</script>

<style>
.footer-bg {
  background-color: #777;
}
#footer {
  max-width: 1080px;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
}
#footer a {
  font-weight: bold;
  font-size: 1.25em;
  margin: 5px;
  padding: 10px;
  border-radius: 5px;
  color: white;
}
#footer a:hover {
  color: #666;
  transition: 0.25s;
}
</style>
