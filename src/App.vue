<template>
  <!-- <NavBar /> -->
  <LoginForm />
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import NavBar from './components/NavBar.vue'
import LoginForm from './components/LoginForm.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // NavBar,
    LoginForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(121, 121, 121);
  margin: 0px;
}

</style>
