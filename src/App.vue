<template>
  <div id="app">
    <img src="./assets/logo.png">
    <TableApi/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import TableApi from './components/Table'
export default {
  name: 'App',
  components: {
    HelloWorld,
    TableApi
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
