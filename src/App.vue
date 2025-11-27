<template>
  <div>
   <Header />
   <Hero />
   <Services />
   <About />
   <Specialist />
   <Contact />
   <Footer />

  </div>
</template>

<script setup>
import { onMounted } from 'vue';
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Services from './components/Services.vue';
import About from './components/About.vue';
import Specialist from './components/Specialist.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import AOS from 'aos'
import 'aos/dist/aos.css'



onMounted(()=> {
AOS.init();
})
 
</script>
