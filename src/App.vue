<template> 
 <header>
   <span class="texto-header">Home</span>
   <span class="separador"> | </span>
   <span class="texto-header">Editoras</span>
   <span class="separador"> | </span>
   <span class="texto-header">Categorias</span>
   <span class="separador"> | </span>
   <span class="texto-header">Autores</span>
   <span class="separador"> | </span>
   <span class="texto-header">Livros</span>
</header>
   <main>Main</main>
   <footer>Rodapé</footer>
</template>

<style>
@import '@/assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  height: 50vh;

  font-weight: normal;
}

header,
footer { 
  background-color: rgb(190, 170, 249);
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
  color:azure;
}
 main {
   
 }
</style>