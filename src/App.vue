<template>
  <div id="app">
    <router-link :to="{ name: 'Main' }">Main</router-link>
    <router-link :to="{ name: 'Dashboard' }">Dashboard</router-link>
    <router-link to="/login">Login</router-link>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #859eb8;
  margin-top: 60px;
}
</style>
