<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppTitle",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    
    <div>
        <h1 class="bg-danger p-4">Buon giorno, la mia prima app con Vite!</h1>
       
    </div>
</template>

<style scoped>
    
    h1{
        color: rgb(255, 253, 253);
    }
</style>