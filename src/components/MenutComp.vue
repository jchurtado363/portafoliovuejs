<template>
  <nav>
    
    <ul>
      <li>Inicio</li>
      <li>Quines somos</li>
      <li>Conocerte es cuidarte</li>
      <li>Agenda tu cita</li>
    </ul>
  </nav>
 
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<style scoped>
ul {
  /*  background:red;  */
  padding: 10px;
  display: flex;
  border: dotted 0.1px;
  width: 100;
  margin: 5em auto;
  align: center;
}

li {
  background: gray;
  margin: 10px auto;
  padding: 4px;
  /*   display: inline-block;  */
  border-radius: 4px;
  width: 5em;
  text-align: center;
}
</style>
