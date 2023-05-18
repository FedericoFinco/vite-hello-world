
<script>
//Importiamo i componenti da usare
import AppTitle from './components/AppTitle.vue'
import AppContent from './components/AppContent.vue'
import casualComponent from './components/casualComponent.vue'

//Definiamo l'oggetto che conterrà la lista dei componenti importati, che vogliamo usare
export default {
  components: {
    AppTitle,
    AppContent,
    casualComponent
  }
}
</script>

<!-- Qui inseriamo l'HTML della nostra App -->
<template>
  <header>
    <!-- Usiamo i componenti importati sopra -->
    <!-- il contenuto è nei relativi file (cartella "components") -->
    <AppTitle />
  </header>

  <main>
    <!-- Usiamo i componenti importati sopra -->
    <!-- il contenuto è nei relativi file (cartella "components") -->
    <AppContent />
    <casualComponent />
  </main>
</template>

<!-- Qui abbiamo eventuale stile del componente "App", che è il contenitore generale -->
<style></style>
