<script setup>
import AppNavbar from './components/AppNavbar.vue'
import HeroSection from './components/HeroSection.vue'
import TechStack from './components/TechStack.vue'
import ProjectsSection from './components/ProjectsSection.vue'
import AboutSection from './components/AboutSection.vue'
import ContactSection from './components/ContactSection.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<template>
  <div class="portfolio-container">
    <AppNavbar />
    <main>
      <HeroSection id="inicio" />
      <TechStack id="tecnologias" />
      <ProjectsSection id="proyectos" />
      <AboutSection id="sobre-mi" />
      <ContactSection id="contacto" />
    </main>
    <AppFooter />
  </div>
</template>

<style scoped>
html {
  scroll-behavior: smooth;
}
</style>
