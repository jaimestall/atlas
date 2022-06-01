<template>
  <div class="nav-bar-bg">
    <div id="nav-bar">
      <a class="logo" href="/">Atlas</a>
      <div class="menu">
        <router-link to="/">Home</router-link>
        <router-link to="/Basico">Básico</router-link>
        <router-link to="/Javascript">Javascript</router-link>
        <router-link to="/SQL">SQL</router-link>
      </div>
    </div>
  </div>
</template>

<style>
.nav-bar-bg {
  background-color: #777;
}
#nav-bar {
  max-width: 1000px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}
.logo {
  font-size: 2.25em !important;
}
#nav-bar a {
  font-weight: bold;
  font-size: 1.25em;
  margin: 5px;
  padding: 10px;
  border-radius: 5px;
  color: white;
}
</style>
