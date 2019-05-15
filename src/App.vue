<template>
  <div id="app">
    <h1>Profile Viewer Vue</h1>
    <LoginButton />
  </div>
</template>

<script>
import { LoginButton } from 'solid-vue-components';

export default {
  name: 'app',
  components: {
    LoginButton
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
button {
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  border-radius: 10px ;
  padding: 15px 30px;
  color: #42b983
}
button:hover {
  cursor: pointer;
  transform: scale(1.1)
}
</style>
