<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "casualComponent"
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <div>
        <h2>ricorda , <span class="pirateria">LA PIRATERIA</span> , è un<span class="reato"> REATO</span></h2>
        <img class="pirateriaImg" src="https://lagazzettadelpubblicitario.it/wp-content/uploads/2022/09/Capture-de%CC%81cran-2022-06-06-a%CC%80-23.16.32.png" alt="">
        
    </div>
</template>
<style scoped>
h2> .pirateria {
    color: rgb(190, 6, 6);
    font-size: 6rem;
    font-weight: bolder;
    text-decoration: underline;
}

h2> .reato {
    color: rgb(190, 6, 6);
}

.pirateriaImg{
    width: 50%;
}
</style>
<!-- Non c'è stile speicifoc per il componente, usiamo solo quanto c'è in  style.css -->