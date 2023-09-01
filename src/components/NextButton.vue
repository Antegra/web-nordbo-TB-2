<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>

    <div class="button">
     <div class="button__legs button__legs__right"></div>
     <div  class="button__legs button__legs__left"></div>
    </div>
    
</template>

<style lang="scss" scoped>

.button {
    width: 0%; 
    height: 100%; 
    position: relative;
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: 30px;
    margin-bottom: 90px;
}

.button__legs {
    width: 43.81px; 
    height: 0px; 
    left: 30.98px; 
    top: 30.98px; 
    position: absolute;
    transform-origin: 0 0; 
    border: 1.50px #3DBFEA solid
}

.button__legs__right {
    transform: rotate(-135deg)
}

.button__legs__left {
    transform: rotate(-45deg)
}





</style>