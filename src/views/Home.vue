<template>
  <div id="home">
    <h2 class="titulo-corpo">O que é um atlas</h2>
    <div class="corpo-item">
      <h2>Dicionário</h2>
      <p>substantivo masculino de duas sílabas</p>
      <p>
        1. publicação constituída por <b>uma coleção de mapas</b> ou de cartas
        geográficas.
      </p>
      <p>
        2. POR EXTENSÃO livro constituído por <b>uma coleção de gravuras</b>,
        gráficos etc., relativos a uma dada ciência. "a. de anatomia"
      </p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {},
};
</script>

<style>
#home {
  max-width: 1100px;
  margin: auto;
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
/* Corpo do site */
.corpo-item {
  background-color: #f0f0f0;
  flex: 1 1 100px;
  margin: 15px;
  padding: 10px 0;
  border: 1px solid #777;
  box-shadow: 1.5px 1.5px 0 #bbb;
}
.corpo-item h2 {
  font-size: 2.25em;
  color: #a4a4a4;
  margin: 0 20px 5px 20px;
  padding-bottom: 10px;
  border-bottom: 3px solid white;
}
.corpo-item p {
  font-size: 1em;
  padding: 0 20px;
  line-height: 1.8;
  color: #7c7c7c;
}
</style>
