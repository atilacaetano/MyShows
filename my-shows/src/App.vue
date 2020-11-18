<template>
  <div id="app1">
    <Login></Login>
  </div>
</template>

<script>
import Login from './components/Login.vue'

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style>
#app1 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: auto;
  color: #2c3e50;
  border-radius: 8px;
  background: #fff;
  max-width: 400px;
  padding: 10px;
  margin-top: 60px;
  -webkit-box-shadow: 0px 10px 26px -8px rgba(0,0,0,0.75);
-moz-box-shadow: 0px 10px 26px -8px rgba(0,0,0,0.75);
box-shadow: 0px 10px 26px -8px rgba(0,0,0,0.75);
  padding-bottom: 50px;
}
body{
  background-color: #109C64 !important;
}

</style>
