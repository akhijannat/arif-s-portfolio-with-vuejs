<script setup>
import { ref, onMounted, onUnmounted } from "vue";

const navLink =
  "flex justify-end items-center space-x-2 py-[3px] inline-block transition duration-1000";
const navDot = "h-3 w-3 rounded-full bg-red-700 transition duration-1000";
const navText =
  "uppercase opacity-0 text-[12px] font-bold  transition duration-1000";

const isVisible = ref(false);

const handleScroll = () => {
  const scrollPosition = window.scrollY;
  const screenHeight = window.innerHeight;

  // Calculate how far the user has scrolled in screens
  const screensScrolled = scrollPosition / screenHeight;

  // Check if the user has scrolled at least one screen
  isVisible.value = screensScrolled >= 1;
};

// Attach scroll event listener when the component is mounted
onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

// Remove scroll event listener when the component is unmounted
onUnmounted(() => {
  window.removeEventListener("scroll", handleScroll);
});
</script>
<template>
  <!-- Navigation -->
  <nav v-if="isVisible" class="fixed right-8 top-1/3 text-right">
    <a href="#intro" :class="navLink" class="nav-item">
      <p :class="navText">Intro</p>
      <div :class="navDot"></div>
    </a>
    <a href="#services" :class="navLink" class="nav-item">
      <p :class="navText">What I Do</p>
      <div :class="navDot"></div>
    </a>
    <a href="#skills" :class="navLink" class="nav-item">
      <p :class="navText">Skills</p>
      <div :class="navDot"></div>
    </a>

    <a href="#workExample" :class="navLink" class="nav-item">
      <p :class="navText">Work Example</p>
      <div :class="navDot"></div>
    </a>

    <a href="#clientExperience" :class="navLink" class="nav-item">
      <p :class="navText">Client Experience</p>
      <div :class="navDot"></div>
    </a>

    <a href="#contact" :class="navLink" class="nav-item">
      <p :class="navText">Contact</p>
      <div :class="navDot"></div>
    </a>
  </nav>

  <!-- Back to top Button -->
  <div v-if="isVisible" class="fixed bottom-10 right-10">
    <a
      href="#welcome"
      class="relative w-10 h-10 flex justify-center items-center rounded-full"
    >
      <span
        class="animate-ping absolute inline-flex h-full w-full rounded-full bg-gradient-to-r from-red-300 via-pink-400 to-red-300"
      >
        🔝
      </span>
      <span
        class="relative inline-flex justify-center items-center text-xl rounded-full w-10 h-10 bg-gradient-to-r from-red-400 via-pink-400 to-red-400"
      >
        🔝
      </span>
    </a>
  </div>
</template>

<style scoped>
.nav-item:hover p {
  color: black;
  opacity: 1;
}
.nav-item:hover div {
  background-color: black;
}
.is-selected div {
  background-color: black;
}
</style>
