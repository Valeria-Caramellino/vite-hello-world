
<script>
//Importiamo i componenti da usare
import AppTitle from './components/AppTitle.vue'
import AppContent from './components/AppContent.vue'

//Definiamo l'oggetto che conterrà la lista dei componenti importati, che vogliamo usare
export default {
  components: {
    AppTitle,
    AppContent
  }
}
</script>

<template>
  <header>
    <AppTitle/>
  </header>
  <main>
    <AppContent/>
  </main>
  
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
h2{
  font-size: 50px !important;
}
</style>
