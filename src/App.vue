<script setup>
import NavBar from './components/NavBar.vue'
import MainCard from './components/MainCard.vue'
import About from './components/About.vue'
import AboutContent from './components/AboutContent.vue'
</script>

<template>
  <header>
    <NavBar/>
  </header>

  <section>
    <MainCard/>
  </section>

  <section>
    <About/>
  </section>

  <section>
    <AboutContent/>
  </section>
</template>


<style scoped>

</style>
