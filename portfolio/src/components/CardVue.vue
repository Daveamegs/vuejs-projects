<script setup>
defineProps({
    btnText: String,
})
</script>

<template>
<div class="card">
    <div class="bg-portfolio-image">
        
    </div>
    <p></p>
    <p><button>{{ btnText }}</button></p>
</div>
</template>

<style scoped>
.card{
    height: 350px;
}
</style>