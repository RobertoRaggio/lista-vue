<template>
  

</template>

<script>
new Vue({
        el: "#app",
        data: {
          usuario: [
            {
              nombre: "Pau",
              apellido: "Capell",
              run: "18633955-4",
              nacimiento: "02-12-88",
              edad: 33
            },
            {
              nombre: "Michael",
              apellido: "Schumacher",
              run: "9867451-0",
              nacimiento: "03-01-1969",
              edad: 53
            },
            {
              nombre: "Magnus",
              apellido: "Carlsen",
              run: "19833821-9",
              nacimiento: "08-09-1993",
              edad: 28
            }
          ]
        }
      });
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
