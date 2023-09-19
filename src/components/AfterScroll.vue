<script setup>
import { ref, onMounted, onUnmounted } from "vue";

const isVisible = ref(false);
const activeItem = ref(null);

const handleScroll = () => {
  const scrollPosition = window.scrollY;
  const screenHeight = window.innerHeight;
  const screensScrolled = scrollPosition / screenHeight;
  isVisible.value = screensScrolled >= 1;

  const categoryPositions = {
    intro: 1,
    services: 2,
    skills: 3,
    workExample: 4,
    clientExperience: 5,
    contact: 6,
  };

  // Determine which category is currently in view
  let currentCategory = null;
  for (const category in categoryPositions) {
    if (scrollPosition >= categoryPositions[category] * screenHeight) {
      currentCategory = category;
    }
  }

  // Map the current category to the corresponding navigation item
  const categoryToItem = {
    intro: 0,
    services: 1,
    skills: 2,
    workExample: 3,
    clientExperience: 4,
    contact: 5,
  };

  // Update the active item based on the current category
  if (categoryToItem[currentCategory] !== undefined) {
    activeItem.value = categoryToItem[currentCategory];
  }
};

const handleItemClick = (itemNumber) => {
  activeItem.value = itemNumber;
};

onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

onUnmounted(() => {
  window.removeEventListener("scroll", handleScroll);
});
</script>
<template>
  <!-- Navigation -->

  <nav
    v-if="isVisible"
    id="dot-nav"
    class="fixed z-[1] top-1/2 right-8 bottom-auto translate-y-[-50%] transition-opacity visible"
  >
    <div class="text-right">
      <a
        href="#intro"
        data-number="0"
        class=""
        @click="handleItemClick(0)"
        :class="{ navLink, 'active-item': activeItem === 0 }"
      >
        <span class="dot"></span>
        <span class="dot-label">Intro</span>
      </a>

      <a
        href="#services"
        data-number="1"
        class=""
        @click="handleItemClick(1)"
        :class="{ navLink, 'active-item': activeItem === 1 }"
      >
        <span class="dot"></span>
        <span class="dot-label">What I Do</span>
      </a>

      <a
        href="#skills"
        data-number="2"
        class=""
        @click="handleItemClick(2)"
        :class="{ navLink, 'active-item': activeItem === 2 }"
      >
        <span class="dot"></span>
        <span class="dot-label">Skills</span>
      </a>

      <a
        href="#workExample"
        data-number="3"
        class=""
        @click="handleItemClick(3)"
        :class="{ navLink, 'active-item': activeItem === 3 }"
      >
        <span class="dot"></span>
        <span class="dot-label">Work Example</span>
      </a>

      <a
        href="#clientExperience"
        data-number="4"
        class=""
        @click="handleItemClick(4)"
        :class="{ navLink, 'active-item': activeItem === 4 }"
      >
        <span class="dot"></span>
        <span class="dot-label">Client Experience</span>
      </a>

      <a
        href="#contact"
        data-number="5"
        class=""
        @click="handleItemClick(5)"
        :class="{ navLink, 'active-item': activeItem === 5 }"
      >
        <span class="dot"></span>
        <span class="dot-label">Contact</span>
      </a>
    </div>
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

#dot-nav .dot {
  height: 20px;
  width: 20px;
  border-radius: 50%;
  background-color: #ff0000;
  transition: transform 0.2s, background-color 0.5s;
  transform-origin: 50% 50%;
}

#dot-nav .dot-label {
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
#dot-nav a.active-item .dot {
  background-color: green;
}
</style>
