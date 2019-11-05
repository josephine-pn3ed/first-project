<template>
  <div id="app">
    <div class="card">
      <NavBar/>
    </div>
    <div class="content">
      <router-view/>
      </div>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'home',
  components: {
    NavBar
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
  margin-top: 0;
}
.content {
  margin-top: 20px;
}
</style>
