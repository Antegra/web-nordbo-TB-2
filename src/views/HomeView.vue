<script setup>
import Information from '../components/Information.vue';
import Robots from '../components/Robots.vue';
import Automation from '../components/Automation.vue';
import Surfaces from '../components/Surfaces.vue';
import Steps from '../components/Steps.vue';
import NextButton from '../components/NextButton.vue';
 


</script>

<template>
  <main>
    <h1>home</h1>
    
  
  
  

  <Steps> </Steps>
  
  <Information> </Information>

  <Robots> </Robots>

  <Automation> </Automation>

  <Surfaces> </Surfaces>

  <NextButton> </NextButton>
  
</main>

</template>

<style lang="scss" scoped>
@import "../assets/scss/colors.scss";




/* codepen override */
html *
{
   font-size: 15px !important;
   color: #000 !important;
   font-family: Arial !important;
}




</style>