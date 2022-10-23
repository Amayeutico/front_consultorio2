<template>
  <div id="app">
    <div><img src="./assets/consultorio.jpg" alt="" /></div>
    <nav id="nav"> |
      <router-link to="/Usuarios">Usuarios</router-link>|
    </nav>
  <div class="contenedor">
    <router-view />
  </div>

  <footer>pie pagina</footer>
</div>
</template>

<style>
.contenedor{
  width: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
