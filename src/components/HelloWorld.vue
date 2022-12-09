<template>
<section>
  <h1>Contacto</h1>
  <article>
    
    <li><img src="..\assets\correo-electronico-vacio.png" alt=""> jchurtado363@misena.edu.co</li><br>
      
      
      <li><img src="..\assets\whatsapp.png" alt=""> 3206546472</li><br>
    
      
      <li> <img src="..\assets\gorjeo.png" alt="">@Macoy83</li>

  </article>
  <div>
  <form action="">
 <label for=""> Nombres</label> 
 <input type="text" placeholder="Ingrese nombres">
 <label for="">Apellidos</label>
   <input type="text" placeholder="Ingrese apellidos">
   <label for="">Email</label>
  <input type="email" placeholder="Ingrese Email" required>
<label for="">Mensaje </label>
   <textarea name="mj" id="mjs" cols="20" rows="10" placeholder="Escribe tu mensaje"></textarea>
  <input type="submit">
  </form>
</div>
</section>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
section{
  justify-content: center;
  height: 100vh;
  display: flex;
}

li {
  display: block;
 
}
article{
  margin: 200px;
  text-align: left;

 display: block; 
}
img {
  height: 30px;
  width: 30px;
}
div{
  margin: 100px;
  
  
}
form{
  width: 100%;
  border:solid 1px;
  margin: 10px;
  padding: 20px;
  background-color: rgb(217, 231, 231);
  
}
label{
  display: block;
  width: 100%;
}

input,textarea{
  margin-bottom: 20px;
  width: 90%;
  padding: 10px;
  border: 1px solid #ccc;
}
input:focus{
  border: 1px solid rgb(244, 79, 79);
}
input[type="submit"]{
  margin-bottom: 0;
  background-color: blueviolet;
  color: #fff;
  border: none;

}
input[type="submit"]:hover{
  background-color: rgb(186, 186, 242);
  cursor: pointer;
}

</style>
