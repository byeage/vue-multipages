<template>
  <div id="admin">
    <h3>Admin</h3>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'admin'
  }
</script>

<style>
  #admin {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
