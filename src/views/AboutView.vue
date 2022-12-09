<template>
<body>
  


<h1>Curriculum</h1>
<ExperienciaComp/>


 
 </body>
</template>
<script>
 import ExperienciaComp from '@/components/ExperienciaComp.vue'
 
export default {
 

  name: 'AboutView',
  components: {

   ExperienciaComp
  
  }
}
</script>

<style scoped>
body{
  
  border: solid 1px;
  
  background-color:rgb(215, 208, 208);
}
h1{
  text-align: left;
  margin: 100px;
}



</style>
