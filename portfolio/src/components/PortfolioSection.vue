<script>
// import CardVue from "./CardVue.vue";

</script>

<template>
    <div id="portfolio-section">
        <h2 class="portfolio-header">Portfolio</h2>
        <div class="portfolio">
            <!-- Card One -->
           <div class="card">
            <div class="bg-portfolio-image">
        
            </div>
            <p class="portfolio-description"></p>
            <p><button></button></p>
            </div>

             <!-- Card Two -->
               <div class="card">
                <div class="bg-portfolio-image">
        
                </div>
                <p class="portfolio-description"></p>
                <p><button></button></p>
                </div>

                 <!-- Card Three -->
               <div class="card">
                <div class="bg-portfolio-image">
        
                </div>
                <p class="portfolio-description"></p>
                <p><button></button></p>
                </div>
        </div>
    </div>
</template>

<style scoped>
#portfolio-section{
    text-align: center;
}

.portfolio{
    display: flex;
    flex-direction: column;
    place-items: center;
}

.card{
    width: 280px;
    height: 350px;
    background-color: yellow;
    margin-bottom: 20px;
}

.bg-portfolio-image{
    width: inherit;
    height: 200px;
    background-color: aqua;
}

.portfolio-description{
    width: inherit;
    height: 50px;
}

</style>