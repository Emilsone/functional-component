<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Test 
     :brands ="['Tesla', 'Bentley', 'Ferrari', 'Ford']">
    </Test>
    <Example>
     Find More Cars
    </Example>
  </div>
</template>
<script>
import Test from './components/Test.vue'
import Example from './example.js'
export default {
  name: 'app',
  components: {
    Test,
    Example,
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
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
