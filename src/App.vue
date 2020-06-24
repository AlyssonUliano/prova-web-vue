<template>
  <div id="app">
    <BuscarCep />
  </div>
</template>

<script>
import BuscarCep from "./components/BuscarCep.vue";

export default {
  name: "App",
  components: {
    BuscarCep
  }
};
</script>

<style>
body {
  background: rgb(217, 243, 225);
}

#app {
  font-family:  Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: arial;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #57a2ee;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
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
  color: #000000;
}
</style>
