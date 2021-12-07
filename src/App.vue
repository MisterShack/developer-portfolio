<script setup>
  import Header from "./components/Header.vue";
  import IntroImage from "./components/IntroImage.vue";
  import AboutMe from "./components/AboutMe.vue";
  import Projects from "./components/Projects.vue";
  import Resume from "./components/Resume.vue";
  import Divider from "./components/Divider.vue";
</script>

<template>
  <div class="relative max-w-screen-xl mx-auto px-8 py-6">
    <Header />
    <main>
      <IntroImage />
      <AboutMe />
      <Divider />
      <Projects />
      <Divider />
      <Resume />
    </main>
  </div>
</template>
