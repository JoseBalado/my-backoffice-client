<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Dashboard</h2>
    <div>
      <iframe src="http://localhost/frontendstats"></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
  data () {
    return {
      msg: 'Incredible useful stats'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
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
  color: #42b983;
}
body { color: #efabdb; }
</style>
