<script setup>
var x = 0 
var y = 0
function moverandom(){
    x = Math.floor(Math.random() * 1000);
    y = Math.floor(Math.random() * 1000);
}
var img = document.getElementById('xenoimage');
img.style.position = "absolute";
img.style.left = x+'px';
img.style.top = y+'px';

</script>

<template>
  
  <body>
    <div @click="moverandom" id = "xenoimage">
        <a href="Xeno.gif"></a>
    </div>
  </body>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
