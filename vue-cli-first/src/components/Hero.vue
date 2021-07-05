<template>
  <div>
    <!-- qui metto il mio h1 dell'esercizio -->
    <div class="jumbotrone">
     <h2>Domodossola (Dòm in dialetto ossolano, Döm in walser) è un comune italiano di 17 930 abitanti[2] della provincia del Verbano-Cusio-Ossola in Piemonte. La città è il centro principale della val d'Ossola e si trova nella piana del fiume Toce, alla confluenza di val Bognanco, val Divedro, valle Antigorio-Formazza, valle Isorno e val Vigezzo.</h2>
     <p>Compra un biglietto aereo per arrivarci :</p>
     <button class="bottone">Accedi al nostro sito</button>
     <button class="bottone">Compra ora i biglietti</button>
      

    </div>
    
    
  </div>
</template>

<script>
export default {
  name: 'Hero'
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.jumbotrone{
  width:70%;
  margin:auto;
  
  
  
  
 
}
p{
  margin-top:50px;
  font-size: 20px;
  color: red;
}
.bottone{
  margin-left: 20px;
  font-size: 20px;
  border: 2px solid black;
}
.bottone:hover{
  opacity:0.6;
}

</style>
