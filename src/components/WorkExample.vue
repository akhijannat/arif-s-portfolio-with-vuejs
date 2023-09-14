<script setup>
import Heading from "../components/Heading.vue";
</script>
<template>
  <section id="workExample" class="bg-gray-50">
    <div class="w-4/5 mx-auto py-10 text-center">
      <Heading>Some of My Work</Heading>
      <div class="h-1 w-52 bg-gray-600 mx-auto rounded-full my-3"></div>

      <div
        class="text-left"
        id="carousel"
        data-flickity='{ "autoPlay": true, "autoPlay": 1500, "prevNextButtons": false, "pageDots": false }'
      >
        <a
          href="#"
          class="carousel-cell mx-5 bg-gradient-to-tr from-slate-200 to-white p-4 rounded-2xl shadow"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-72 w-[500px] rounded"
            src="../assets/Home-Real-Fruit.png"
          />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>

        <a
          href="#"
          class="carousel-cell mx-5 bg-gradient-to-tr from-slate-200 to-white p-4 rounded-2xl shadow"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-72 w-[500px] rounded"
            src="../assets/Home-Real-Fruit.png"
          />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>

        <a
          href="#"
          class="carousel-cell mx-5 bg-gradient-to-tr from-slate-200 to-white p-4 rounded-2xl shadow"
          style="font-family: 'Bentham', serif"
        >
          <img class="h-72 w-[500px] rounded" src="../assets/wb-1.jpg" />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>

        <a
          href="#"
          class="carousel-cell mx-5 bg-gradient-to-tr from-slate-200 to-white p-4 rounded-2xl shadow"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-72 w-[500px] rounded"
            src="../assets/Home-Real-Fruit.png"
          />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>

        <a
          href="#"
          class="carousel-cell mx-5 bg-gradient-to-tr from-slate-200 to-white p-4 rounded-2xl shadow"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-72 w-[500px] rounded"
            src="../assets/Home-Real-Fruit.png"
          />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>
      </div>
    </div>
  </section>
</template>
<style scoped></style>
