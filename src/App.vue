<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
body,
html {
  margin: 0;
}
#app {
  font-family: "Roboto", -apple-system, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #883f34;
  color: #f6f6f6;
  min-height: 100vh;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #fff;
    &.router-link-exact-active {
      color: #c9c565;
    }
  }
}
</style>
