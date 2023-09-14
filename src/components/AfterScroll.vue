<script setup>
import { ref, onMounted, onUnmounted } from "vue";

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
  <nav
    v-if="isVisible"
    id="dot-nav"
    class="active fixed z-[1] top-1/2 right-8 bottom-auto translate-y-[-50%] transition-[visibility 0s, opacity 0.5s ease] invisible opacity-0"
  >
    <ul class="text-right">
      <li>
        <a href="#intro" data-number="0" class="is-selected">
          <span class="dot"></span>
          <span class="dot-label">Intro</span>
        </a>
      </li>
      <li>
        <a href="#services" data-number="1" class="is-selected">
          <span class="dot"></span>
          <span class="dot-label">What I Do</span>
        </a>
      </li>
      <li>
        <a href="#skills" data-number="2" class="is-selected">
          <span class="dot"></span>
          <span class="dot-label">Skills</span>
        </a>
      </li>
      <li>
        <a href="#workExample" data-number="3" class="is-selected">
          <span class="dot"></span>
          <span class="dot-label">Work Example</span>
        </a>
      </li>
      <li>
        <a href="#clientExperience" data-number="4" class="is-selected">
          <span class="dot"></span>
          <span class="dot-label">Client Experience</span>
        </a>
      </li>
      <li>
        <a href="#contact" data-number="5" class="is-selected">
          <span class="dot"></span>
          <span class="dot-label">Contact</span>
        </a>
      </li>
    </ul>
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
#dot-nav.active {
  visibility: visible;
  opacity: 1;
  transition: visibility 0s, opacity 0.5s ease;
}

#dot-nav a::after {
  clear: both;
  content: "";
  display: table;
}

#dot-nav a span {
  float: right;
  display: inline-block;
  transform: scale(0.6);
}

#dot-nav a:hover span {
  transform: scale(0.75);
}

#dot-nav a .is-selected .dot {
  background-color: #000;
}

#dot-nav .dot {
  position: relative;
  top: 7px;
  height: 20px;
  width: 20px;
  border-radius: 50%;
  background-color: red;
  transition: transform 0.2s, background-color 0.5s;
  transform-origin: 50% 50%;
}

#dot-nav .dot-label {
  position: relative;
  top: 3px;
  padding-right: 5px;
  color: #000;
  font-size: 17px;
  font-weight: 500;
  text-transform: uppercase;
  opacity: 0;
  transition: transform 0.2s, opacity 0.2s;
  transform-origin: 100% 50%;
}
#dot-nav a:hover .dot-label {
  opacity: 1;
}
</style>
