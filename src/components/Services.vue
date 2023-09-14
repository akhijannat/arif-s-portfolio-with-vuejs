<script setup>
import Heading from "../components/Heading.vue";

const servicesSection =
  "bg-[url('https://plus.unsplash.com/premium_photo-1674729243673-0b5e871a8a24?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1535&q=80')] py-10 bg-cover bg-center bg-no-repeat";
</script>

<template>
  <section id="services" :class="servicesSection">
    <div class="w-4/5 mx-auto text-center">
      <Heading>What I Do</Heading>

      <div class="h-1 w-52 bg-gray-600 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-2 md:py-10 text-white">
        <div class="md:border-r border-slate-300 md:border-b p-2 md:p-7">
          <div
            class="flex space-x-2 text-2xl md:text-3xl items-center font-bold"
            style="font-family: 'Bentham', serif"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M9 17.25v1.007a3 3 0 01-.879 2.122L7.5 21h9l-.621-.621A3 3 0 0115 18.257V17.25m6-12V15a2.25 2.25 0 01-2.25 2.25H5.25A2.25 2.25 0 013 15V5.25m18 0A2.25 2.25 0 0018.75 3H5.25A2.25 2.25 0 003 5.25m18 0V12a2.25 2.25 0 01-2.25 2.25H5.25A2.25 2.25 0 013 12V5.25"
              />
            </svg>

            <h2 class="">Web Development</h2>
          </div>

          <p class="mt-5 italic">
            Using HTML, CSS, and JavaScript with pre-processors and build tools
            such as Sass and Grunt, I have a passion for developing
            pixel-perfect websites and apps while maintaining a semantic,
            modular, and DRY code base.
          </p>
        </div>

        <div class="md:border-b border-slate-300 p-2 md:p-7">
          <div
            class="flex space-x-2 text-2xl md:text-3xl items-center font-bold"
            style="font-family: 'Bentham', serif"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-8 h-8"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M14.25 9.75L16.5 12l-2.25 2.25m-4.5 0L7.5 12l2.25-2.25M6 20.25h12A2.25 2.25 0 0020.25 18V6A2.25 2.25 0 0018 3.75H6A2.25 2.25 0 003.75 6v12A2.25 2.25 0 006 20.25z"
              />
            </svg>
            <h2 class="">RESPONSIVE UI DESIGN</h2>
          </div>

          <p class="mt-5 italic">
            Using HTML, CSS, and JavaScript with pre-processors and build tools
            such as Sass and Grunt, I have a passion for developing
            pixel-perfect websites and apps while maintaining a semantic,
            modular, and DRY code base.
          </p>
        </div>

        <div class="md:border-r border-slate-300 p-2 md:p-7">
          <div
            class="flex space-x-2 text-2xl md:text-3xl items-center font-bold"
            style="font-family: 'Bentham', serif"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M8.25 7.5V6.108c0-1.135.845-2.098 1.976-2.192.373-.03.748-.057 1.123-.08M15.75 18H18a2.25 2.25 0 002.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 00-1.123-.08M15.75 18.75v-1.875a3.375 3.375 0 00-3.375-3.375h-1.5a1.125 1.125 0 01-1.125-1.125v-1.5A3.375 3.375 0 006.375 7.5H5.25m11.9-3.664A2.251 2.251 0 0015 2.25h-1.5a2.251 2.251 0 00-2.15 1.586m5.8 0c.065.21.1.433.1.664v.75h-6V4.5c0-.231.035-.454.1-.664M6.75 7.5H4.875c-.621 0-1.125.504-1.125 1.125v12c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V16.5a9 9 0 00-9-9z"
              />
            </svg>

            <h2 class="">EXPERIENCE DESIGN</h2>
          </div>

          <p class="mt-5 italic">
            Using HTML, CSS, and JavaScript with pre-processors and build tools
            such as Sass and Grunt, I have a passion for developing
            pixel-perfect websites and apps while maintaining a semantic,
            modular, and DRY code base.
          </p>
        </div>

        <div class="p-2 md:p-7">
          <div
            class="flex space-x-2 text-2xl md:text-3xl items-center font-bold"
            style="font-family: 'Bentham', serif"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582M12 3a8.997 8.997 0 00-7.843 4.582m15.686 0A11.953 11.953 0 0112 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0121 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0112 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 013 12c0-1.605.42-3.113 1.157-4.418"
              />
            </svg>

            <h2 class="">DIVERSITY IN TECH</h2>
          </div>

          <p class="mt-5 italic">
            Using HTML, CSS, and JavaScript with pre-processors and build tools
            such as Sass and Grunt, I have a passion for developing
            pixel-perfect websites and apps while maintaining a semantic,
            modular, and DRY code base.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
