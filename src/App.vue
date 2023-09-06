<script setup>
import Welcomeview from "./components/WelcomeView.vue";
import Intro from "./components/Intro.vue";
import Services from "./components/Services.vue";
import Skills from "./components/Skills.vue";
import WorkExample from "./components/WorkExample.vue";
import ClientExperience from "./components/ClientExperience.vue";
import Contact from "./components/Contact.vue";
</script>
<template>
  <Welcomeview />
  <Intro />
  <Services />
  <Skills />
  <WorkExample />
  <ClientExperience />
  <Contact />

  <!-- Footer -->
  <footer class="bg-[#99aec2] italic py-4">
    <div class="text-center">
      <p>&copy; 2023 Arif Hosen - All Rights Reserved</p>
    </div>
  </footer>
</template>
