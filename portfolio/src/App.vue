<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue';
import IntroSection from "./components/IntroSection.vue";
import PortfolioSection from "./components/PortfolioSection.vue";
import ContactForm from "./components/ContactForm.vue";
import ElevatorPitch from "./components/ElevatorPitch.vue";
</script>

<template>
  <NavBar />
  <main>
    <IntroSection />
    <ElevatorPitch />
    <PortfolioSection />
    <ContactForm />
  </main>
  <footer class="footer">
    <p>&copy; 2023 | All Rights Reserved</p>
  </footer>

</template>

<style scoped>
.footer{
  height: 30px;
  text-align: center;
  display: flex;
  flex-direction: column;
}
</style>
