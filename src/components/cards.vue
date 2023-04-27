<script setup>

</script>

<template>
    <div class="space"></div> 
    <div class="p-card">
        <img class="card-img" src="../assets/img/Sanding.png">
        <h3 class="card-title">Sanding</h3>
    </div>
</template>


<style lang="scss" scoped>

@import "../assets/scss/colors.scss";
@import "../assets/scss/typography.scss";

    .p-card { 
        width: 260px;
        height: 206px;
        border-radius: 30px;
        border: 2px solid $Madison;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background: rgb(2,33,92);
        background: linear-gradient(0deg, rgba(2,33,92,1) 24%, rgba(2,33,92,0) 24%);
    }

    .card-img{
        height: 89px;
        max-width: 123px;
    }

    .card-title{
        
    }

    .space {
        padding-top: 200px;
    }
</style>
