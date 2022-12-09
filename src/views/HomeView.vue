<template>
  <body>
    <div>
   
    <PersonalesComp />
  </div>
  <footer>
    
      <article>
      <li><img src="..\assets\correo-electronico-vacio.png" alt=""> jchurtado363@misena.edu.co</li>
      </article>
      <article>
      <li><img src="..\assets\whatsapp.png" alt=""> 3206546472</li>
      </article>
      <article>
      <li> <img src="..\assets\gorjeo.png" alt="">@Macoy83</li>
      </article>
    
  </footer>
  </body>
</template>

<script>
// @ is an alias to /src
 //import MenutComp from '@/components/MenutComp.vue'
//import HelloWorld from '@/components/HelloWorld.vue'
import PersonalesComp  from '@/components/PersonalesComp.vue'
export default {
  name: 'HomeView',
  components: {
    PersonalesComp
    //HelloWorld,MenutComp
  }
}
</script>
<style scoped>
body{
  border: solid 1px;
  background-color: rgb(215, 208, 208);
}
footer{
  width: 100%;
  height: 20vh;
  display: flex;
  justify-content:center;
}
img{
  width: 50px;
  height: 50px;
}
li{
  
  
  list-style: none;

}
article{
  margin: 50px;
  justify-content: center;
}

</style>
