
<script setup>
import {ref} from 'vue'
import { reactive } from 'vue'

const x = 0
const y = 0
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
    <div @click="moverandom" id = "xenoimage">
        <a href="Xeno.gif"></a>
    </div>
</template>
