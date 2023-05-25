<script setup>
import { RouterLink, RouterView } from 'vue-router';
import Cards from './Cards.vue';
import Input from './Input.vue';
</script>

<template>

  <div class="main">

    <Input></Input>

    <Cards> </Cards>
  </div>  
    
</template>

<style lang="scss" scoped>

@import "../assets/scss/colors.scss";
@import "../assets/scss/typography.scss";

img{
    max-width: 100%;
    display: block;
  }

.main{
  width: min(90ch, 100% - 4rem);
  margin-inline: auto;
}

</style>
