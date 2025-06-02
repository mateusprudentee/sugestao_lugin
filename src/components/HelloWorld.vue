<template>
  <div class="hello">
    <h1></h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
body {
  background: black;
  color: white; /* Adiciona uma cor de texto clara para contraste */
  margin: 0; /* Remove margens padrão do body */
  font-family: Arial, sans-serif; /* Define uma fonte padrão */
}

h1 {
  margin: 40px 0; /* Altera a margem do h1 */
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983; /* Cor dos links */
}

a:hover {
  color: #ff9800; /* Cor dos links ao passar o mouse */
}
</style>
