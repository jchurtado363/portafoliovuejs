<template>
<body>
  <h1>Proyectos</h1>
  <DatosacadComp/>
</body>
      
</template>
<script>
import DatosacadComp from '@/components/DatosacadComp.vue'
export default {
   name: 'Hoja1Vista',
  components: {
    
    DatosacadComp
   
  
  }
}
</script>
<style scoped>
body{
  background-color: rgb(215, 208, 208);
  border: solid 1px;
}
h1{
   text-align:left;
   margin: 100px;
}


</style>