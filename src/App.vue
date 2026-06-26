<template>
  <div id="law-firm">
    <Navbar />
    <main>
      <Hero />
      <About />
      <Attorneys />
      <Areas />
      <Services />
      <Process />
      <Credentials />
      <Contact />
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Areas from './components/Areas.vue'
import Services from './components/Services.vue'
import Process from './components/Process.vue'
import Credentials from './components/Credentials.vue'
import Attorneys from './components/Attorneys.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
</script>
