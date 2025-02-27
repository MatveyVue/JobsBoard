<template>
<body>
<div>
<RouterLink to="/profile">
    <img src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 40px; float: right; margin-right: 10px; margin-top: 10px;">
</RouterLink>
</div>

<div>
    <h1>Jobs:</h1>
    <div style="overflow-x: scroll;">
        <button class="categories" style="background-color: #97f492; color: black;">All</button>
        <button class="categories">Programm</button>
        <button class="categories">Ads</button>
    </div>
</div>

<div>
<button @click="open = true" class="jobs1">
<div>
    <img class="img" src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 30px; float: left; margin-top: 10px; margin-left: 10px;">
    <p class="nick">Whsxg</p>
    <p class="work">Frontend Deveoloper</p>
    <p class="info">Разработка Telegram Mini App</p><br>
    <p class="info" style="margin-left: 8px; margin-top: -12px;">по задонному техническому заданию</p>
</div>
<div style="display: inline-flex; margin-top: -115px; float: left;">
    <div class="lang"><p style="margin-top: 5px; margin-left: -3px;">JavaScript</p></div>
    <div class="lang"><p style="margin-top: 5px; margin-left: -3px;">Rust</p></div>
</div>
</button>

<div v-if="open" class="modal">
<div style="margin-top: 20px; margin-left: 20px;">
    <img class="img" src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 30px; float: left; margin-top: 10px; margin-left: 10px;">
    <p class="nick">Whsxg</p>
    <p class="work">Frontend Deveoloper</p>
    <p class="info">Разработка Telegram Mini App</p><br>
    <p class="info" style="margin-left: 8px; margin-top: -12px;">по задонному техническому заданию</p>
</div>
<div style="display: inline-flex; margin-top: -110px; float: left; margin-left: 20px;">
    <div class="lang"><p style="margin-top: 5px; margin-left: 10px;">JavaScript</p></div>
    <div class="lang"><p style="margin-top: 5px; margin-left: 30px;">Rust</p></div>
</div>
    <button class="contact"><b>Contact</b></button>
    <button @click="open = false" class="close">X</button>
</div>
</div>

<div>
<button @click="open1 = true" class="jobs1">
<div>
    <img class="img" src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 30px; float: left; margin-top: 10px; margin-left: 10px;">
    <p class="nick">Whsxg</p>
    <p class="work">Frontend Deveoloper</p>
    <p class="info">Разработка Telegram Mini App</p><br>
    <p class="info" style="margin-left: 8px; margin-top: -12px;">по задонному техническому заданию</p>
</div>
<div style="display: inline-flex; margin-top: -115px; float: left;">
    <div class="lang"><p style="margin-top: 5px; margin-left: -3px;">JavaScript</p></div>
    <div class="lang"><p style="margin-top: 5px; margin-left: -3px;">Rust</p></div>
</div>
</button>

<div v-if="open1" class="modal">
<div style="margin-top: 20px; margin-left: 20px;">
    <img class="img" src="https://i.postimg.cc/FK8K0bcd/IMG-1157.png" style="width: 30px; float: left; margin-top: 10px; margin-left: 10px;">
    <p class="nick">Whsxg</p>
    <p class="work">Frontend Deveoloper</p>
    <p class="info">Разработка Telegram Mini App</p><br>
    <p class="info" style="margin-left: 8px; margin-top: -12px;">по задонному техническому заданию</p>
</div>
<div style="display: inline-flex; margin-top: -110px; float: left; margin-left: 20px;">
    <div class="lang"><p style="margin-top: 5px; margin-left: 10px;">JavaScript</p></div>
    <div class="lang"><p style="margin-top: 5px; margin-left: 30px;">Rust</p></div>
</div>
    <button class="contact"><b>Contact</b></button>
    <button @click="open1 = false" class="close">X</button>
</div>
</div>
</body>
</template>
    
<script setup>
import { ref } from 'vue'

const open = ref(false)
const open1 = ref(false)
</script>
    
