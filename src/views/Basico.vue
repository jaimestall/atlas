<template>
  <div id="basico">
    <h2 class="titulo-corpo">Comandos Básicos</h2>
    <div class="cards-box">
      <div class="card">
        <h2>Comandos gerais</h2>
        <ul type="none">
          <li><span class="code-bold">cd</span> Entra em uma determinada pasta</li>
          <li><span class="code-bold">cd ..</span> Volta uma pasta</li>
          <li><span class="code-bold">pwd</span> Informa o nome da pasta</li>
          <li><span class="code-bold">touch</span> Cria um arquivo</li>
          <li><span class="code-bold">mkdir</span> Cria uma pasta</li>
          <li><span class="code-bold">clear</span> Limpa o prompt</li>
          <li><span class="code-bold">ls</span> Lista os itens que estão na pasta atual</li>
          <li><span class="code-bold">less</span> Exibe o texto do arquivo</li>
          <li><span class="code-bold">mv 'a' 'b'</span> Move o arquivo 'a' para o destino 'b'</li>
          <li><span class="code-bold">code .</span> Abre o VSCode</li>
          <li><span class="code-bold">rmdir 'nome'</span> Apaga uma pasta</li>
        </ul>
      </div>
      <div class="card">
        <h2>Comandos Git</h2>
        <ul type="none">
          <li><span class="code-bold">init</span> Iniciar o versionamento em uma pasta</li>
          <li><span class="code-bold">status</span> Checar a situação dos arquivos</li>
          <li><span class="code-bold">diff</span> Para verificar o que mudou nos arquivos</li>
          <li><span class="code-bold">add .</span> Para salvar os arquivos editados</li>
          <li><span class="code-bold">checkout</span> Para trocar entre branches</li>
          <li><span class="code-bold">commit -m "comentário"</span> Para enviar as alterações</li>
          <li><span class="code-bold">branch nome</span> Cria uma nova branch </li>
          <li><span class="code-bold">branch</span> Verifica lista de branches </li>
          <li><span class="code-bold">merge nome</span> Faz o merge da branch selecionada</li>
          <li><span class="code-bold">push</span> Empurra atualizações para a branch principal</li>
          <li><span class="code-bold">pull</span> Puxa as últimas atualizações da branch principal</li>
        </ul>
      </div>
      <div class="card">
        <h2>Comandos VSCode</h2>
        <ul type="none">
          <li><span class="code-bold">init</span> Iniciar o versionamento em uma pasta</li>
          <li><span class="code-bold">status</span> Checar a situação dos arquivos</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
  export default {};
</script>

<style>
#basico {
  max-width: 1100px;
  margin: auto;
}
</style>
