<template>
  <main>
    <h1></h1>
    <article id="artic1">
      <img src="..\assets\perfil.jpeg" />
    </article>

    <article id="info">
      <ul>
        <h1>Informacion personal</h1>
        <br />
        <li>Nombres : Juan Climaco</li>

        <li>Apellidos : Hurtado Ulchur</li>

        <li>Tipo y numero de documento : Cc 10756363</li>
        <br />

        <li>Fecha de nacimiento : 01 agosto 1983</li>

        <li>Libreta militar clase y numero : Primera - 10756363</li>

        <li>Direccion : Clle 14a 19-56 Popayan Cauca</li>
      </ul>
    </article>
  </main>
</template>
<script>
export default {
  name: "PersonalesComp",
};
</script>
<style scoped>
main {
  width: 100%;
  height: 80vh;
  display: flex;
}

li {
  text-align: center;
  list-style: none;
}
img {
  border-radius: 40%;
  height: 400px;
  width: 320px;
  border: solid 3px;
  margin: 20px;
}
#artic1 {
  position: sticky;
  top: 0px;
  margin: 100px, 100px;
  text-align: center;
}
article {
  margin: 100px;

  justify-content: center;
  width: 100%;
}
h1 {
  justify-content: center;
}
#info {
  margin: 150px;
  justify-content: center;
}
</style>