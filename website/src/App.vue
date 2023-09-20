<template>
  <img alt="fish" src="./assets/Xeno.gif">
  <HelloWorld msg="Welcome to the FishZone"/>
  <HelloWorld msg2="This Site is a WIP, come back later."/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #4c2c50;
  margin-top: 40px;
  margin-bottom: 20px;
}
</style>
