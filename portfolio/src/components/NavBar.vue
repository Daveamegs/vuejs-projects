<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <nav class="navbar">
    <div class="logo">
      <span>David Amegayibor</span>
    </div>
    <div>
      <ul class="nav-list">
        <li><a href="">Home</a></li>
        <li class="about-me-link"><a href="">About Me</a></li>
        <li><a href="">Portfolio</a></li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
.navbar {
  display: flex;
  place-items: center;
  background-color: #65a3;
  padding: 20px;
}

@media only screen and (min-width: 600px){
  .navbar{
    display: flex;
    justify-content: space-between;
  }

  .nav-list{
    display: flex;
    justify-content: space-around;
  }

  .about-me-link{
    margin: 0 20px;
  }

}
</style>
