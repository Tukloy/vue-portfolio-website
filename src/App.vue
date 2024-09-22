<script setup>
import Navbar from '@/components/Navbar.vue'
import Hero from '@/components/Hero.vue'
import AboutMe from '@/components/AboutMe.vue'
import Education from '@/components/Education.vue'
import Skills from '@/components/Skills.vue'
import Contact from '@/components/Contact.vue'
import Footer from '@/components/Footer.vue'
import { reactive } from 'vue'

const state = reactive({
  skills: [
    { name: 'html', image: '/icon/html.png' },
    { name: 'css', image: '/icon/css.png' },
    { name: 'Javascript', image: '/icon/js.png' },
    { name: 'vue 3', image: '/icon/vue.png' },
    { name: 'tailwind', image: '/icon/tailwind.png' },
    { name: 'git', image: '/icon/git.png' },
    { name: 'java', image: '/icon/java.png' },
  ]
})
</script>
<template>
  <div class="">
    <Navbar />
    <div class="flex flex-col">
      <Hero />
      <AboutMe />
      <Education />
      <Skills :skills="state.skills" />
      <Contact />
    </div>
    <Footer />
  </div>
</template>