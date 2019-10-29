<template>
  <div class="navbar">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
.navbar {
  font-size:25px;
  background-color: pink;
  overflow: hidden;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
</style>
