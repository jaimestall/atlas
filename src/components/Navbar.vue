<template>
  <div class="nav-bar-bg">
    <div id="nav-bar">
      <div class="logo"><a href="/">Atlas</a></div>
      <div class="menu">
        <router-link to="/">Home</router-link>
        <router-link to="/Basico">Básico</router-link>
        <router-link to="/Javascript">Javascript</router-link>
        <router-link to="/SQL">SQL</router-link>
      </div>
      <div class="menu-mobile">
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
  max-width: 1080px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}
.menu-mobile {
  display: none;
}
.logo {
  padding: 10px;
  margin: 5px;
}
.logo a {
  font-weight: bold;
  font-size: 2.25em;
  color: white;
  padding: 5px 10px;
}
.logo a:hover {
  color: #666;
  transition: 0.5s;
}
.menu a {
  font-weight: bold;
  font-size: 1.25em;
  margin: 5px;
  padding: 10px;
  color: white;
}
.menu a:hover {
  color: #666;
  transition: 0.5s;
}

@media screen and (max-width: 500px) {
  .menu {
    display: none;
  }
  #nav-bar {
    justify-content: center;
    flex-direction: column;
  }
  .menu-mobile {
    font-weight: bold;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .menu-mobile a {
    font-size: 1.25em;
    margin: 1px;
    padding: 1px;
    color: white;
  }
}
</style>
