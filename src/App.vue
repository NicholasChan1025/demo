<template>
  <div id="app">
    <div class="router-view">
      <router-view />
    </div>
    <div class="copy_right">
      <p>©mi.com 京ICP证110507号 京ICP备10046444号</p>
    </div>
  </div>
</template>

<style>
* {
  padding: 0;
  margin: 0;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  -moz-background-size: 100% 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  display: flex;
  flex-direction: column;
}

#nav {
  padding: 30px;
  margin-left: 65%;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.router-view {
  position: relative;
  flex-grow: 1;
}
.copy_right {
  width: 100%;
  flex-shrink: 0;
  padding: 13px 10px 10px 10px;
  background: #d3d3d3;
  text-align: center;
  font-size: 10px;
  color: #515151;
}
</style>
