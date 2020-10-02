<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">HOME</router-link>
      <router-link to="/about">ABOUT</router-link>
    </div>
    <router-view></router-view>
  </div>
</template>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  color: darkkhaki;
}
#nav {
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: darkorchid;
}
#nav a.router-link-exact-active {
  color: darkolivegreen;
}
</style>
