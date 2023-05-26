<script setup>

</script>

<template>
<<<<<<< Updated upstream
    <div class="section-title">
        <h3>Which processes do you want to automate?</h3>
    </div>


    <div class="card-grid">
        <div class="p-card">
            <img class="card-img" src="../assets/img/Sanding.png">
            <div class="text-box">
                <h3 class="card-title">Sanding</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Grinding.png">
            <div class="text-box">
                <h3 class="card-title">Grinding</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Finishing.png">
            <div class="text-box">
                <h3 class="card-title">Finishing</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Deburring.png">
            <div class="text-box">
                <h3 class="card-title">Deburring</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Painting.png">
            <div class="text-box">
                <h3 class="card-title">Painting/dipensing</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Quality.png">
            <div class="text-box">
                <h3 class="card-title">Quality Control</h3>
            </div>
        </div>
    </div>    
=======
    
     
    
>>>>>>> Stashed changes
    




    <div class="section-title">
        <h3>Which processes do you want to automate?</h3>
    </div>


    <div class="card-grid">
        <div class="p-card">
            <img class="card-img" src="../assets/img/Sanding.png">
            <div class="text-box">
                <h3 class="card-title">Sanding</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Grinding.png">
            <div class="text-box">
                <h3 class="card-title">Grinding</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Finishing.png">
            <div class="text-box">
                <h3 class="card-title">Finishing</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Deburring.png">
            <div class="text-box">
                <h3 class="card-title">Deburring</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Painting.png">
            <div class="text-box">
                <h3 class="card-title">Painting/dipensing</h3>
            </div>
        </div>

        <div class="p-card">
            <img class="card-img" src="../assets/img/Quality.png">
            <div class="text-box">
                <h3 class="card-title">Quality Control</h3>
            </div>
        </div>
    </div>



</template>


<style lang="scss" scoped>

@import "../assets/scss/colors.scss";
@import "../assets/scss/typography.scss";

<<<<<<< Updated upstream

=======
>>>>>>> Stashed changes
    .card-grid{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    .p-card { 
        width: 260px;
        height: 206px;
        border-radius: 30px;
        border: 1px solid $Madison;
        flex: 0 32%;
        margin-bottom: 2%;
        position: relative;
        background: rgb(2,33,92);
        background: linear-gradient(0deg, rgba(2,33,92,1) 20%, rgba(2,33,92,0) 20%);
        text-align: center;
    }


    .text-box{
        position: absolute;
        bottom: -15px;
        left: 0px;
        width: 100%;
    }

    .card-img{
        height: 89px;
        max-width: 123px;
        position: absolute;
        top: 40%;
        transform: translate(-50%, -50%);
    }

    .card-title{
        color: white;
    }

    .section-title{
        color: $Madison;
    }

</style>
