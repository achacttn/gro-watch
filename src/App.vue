<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Grocery.watch</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/groceries">Groceries</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="less">
html, body {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: grid;
  margin: 0px 0px 0px 0px;
}

#app {
  text-align: left;
  color: #2c3e50;
  border: 2px dotted red;
}
#nav {
  border: 2px solid black;
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    margin: 0px 15px 0px 15px;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
