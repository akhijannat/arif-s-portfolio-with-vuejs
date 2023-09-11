<script setup></script>
<template>
  <!-- Welcome Section -->
  <section
    id="welcome"
    class="h-screen flex flex-col justify-center items-center bg-[url('https://images.unsplash.com/photo-1623479322729-28b25c16b011?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80')] bg-cover bg-center bg-no-repeat"
  >
    <div
      class="bg-gradient-to-r from-red-300 via-indigo-400 to-red-300 p-16 rounded-2xl opacity-75 text-center"
    >
      <h1
        class="text-4xl md:text-8xl font-semibold mb-3"
        style="font-family: 'Bentham', serif"
      >
        Arif Hosen
      </h1>
      <p class="sm:text-3xl italic">Full Stack Web Developer</p>
    </div>

    <a
      href="#intro"
      class="animate-bounce w-16 h-16 bg-gradient-to-r from-red-300 via-indigo-400 to-red-300 flex justify-center items-center rounded-full border shadow-2xl mt-20"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="black"
        class="w-8 h-8 transform transition duration-500 hover:scale-125"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M12 3.75v16.5M2.25 12h19.5M6.375 17.25a4.875 4.875 0 004.875-4.875V12m6.375 5.25a4.875 4.875 0 01-4.875-4.875V12m-9 8.25h16.5a1.5 1.5 0 001.5-1.5V5.25a1.5 1.5 0 00-1.5-1.5H3.75a1.5 1.5 0 00-1.5 1.5v13.5a1.5 1.5 0 001.5 1.5zm12.621-9.44c-1.409 1.41-4.242 1.061-4.242 1.061s-.349-2.833 1.06-4.242a2.25 2.25 0 013.182 3.182zM10.773 7.63c1.409 1.409 1.06 4.242 1.06 4.242S9 12.22 7.592 10.811a2.25 2.25 0 113.182-3.182z"
        />
      </svg>
    </a>
    <span class="border-b border-dashed text-xl text-white font-semibold"
      >Click 👇</span
    >
  </section>

  <!-- Intro Section -->
  <section id="intro" class="relative">
    <!-- Navigation -->
    <nav id="dot-nav" class="active">
      <ul>
        <li class="dot-container">
          <a href="#intro" data-number="0" class="">
            <span class="dot"></span> <span class="dot-label">Intro</span>
          </a>
        </li>
        <li class="dot-container">
          <a href="#services" data-number="2">
            <span class="dot"></span> <span class="dot-label">What I Do</span>
          </a>
        </li>
        <li class="dot-container">
          <a href="#skills" data-number="3">
            <span class="dot"></span> <span class="dot-label">Skills</span>
          </a>
        </li>
        <li class="dot-container">
          <a href="#workExample" data-number="4">
            <span class="dot"></span>
            <span class="dot-label">Work Example</span>
          </a>
        </li>
        <li class="dot-container">
          <a href="#clientExperience" data-number="5">
            <span class="dot"></span>
            <span class="dot-label">Client Experience</span>
          </a>
        </li>
        <li class="dot-container">
          <a href="#contact" data-number="6">
            <span class="dot"></span> <span class="dot-label">Contact</span>
          </a>
        </li>
      </ul>
    </nav>

    <div class="">
      <div
        class="w-4/5 mx-auto grid grid-cols-1 md:grid-cols-2 gap-5 md:gap-20 py-5 md:py-10"
      >
        <div
          class="flex justify-center flex-col bg-gradient-to-tr from-slate-200 to-white p-5 rounded-xl shadow-lg shadow-slate-300"
        >
          <h1
            class="text-4xl md:text-[50px] font-bold"
            style="font-family: 'Bentham', serif"
          >
            Hi, I'm Arif Hosen
          </h1>
          <p class="text-lg italic">Full-Stack Web Developer</p>
          <p class="mt-3">
            I'm a top-rated freelancer on Upwork with expertise in HTML, CSS,
            Bootstrap, Tailwind CSS, JavaScript, PHP, Laravel, Vue.js, and
            Alpine JS.
          </p>
          <p class="mt-3">
            I'm a top-rated freelancer on Upwork with expertise in HTML, CSS,
            Bootstrap, Tailwind CSS, JavaScript, PHP, Laravel, Vue.js, and
            Alpine JS.
          </p>
        </div>

        <img
          class="h-[300px] md:h-[400px] bg-indigo-200 shadow-lg shadow-slate-300"
          src="./assets/arif001-Recovered.png"
          alt=""
        />
      </div>
    </div>

    <div class="text-center py-10">
      <h1
        class="text-4xl md:text-[50px] font-bold flex flex-col"
        style="font-family: 'Bentham', serif"
      >
        Why You Hire Me?
      </h1>

      <div class="h-1 w-52 bg-slate-400 mx-auto rounded-full my-3"></div>
      <p class="w-full md:w-1/2 mx-auto">
        Over the past years, I created 50s of websites for my clients. I pride
        myself on doing quality work and maintain excellent communication. I
        enjoy working with include ReactJS, JavaScript as well as Laravel.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-5 items-center gap-5 mt-5">
        <div></div>
        <div
          class="bg-gradient-to-tr from-slate-200 to-white py-5 rounded-xl shadow-xl"
          style="font-family: 'Bentham', serif"
        >
          <h1 class="text-5xl">100 %</h1>
          <p>SUCCESS RATE</p>
        </div>
        <div
          class="bg-gradient-to-tr from-slate-200 to-white py-5 rounded-xl shadow-xl"
          style="font-family: 'Bentham', serif"
        >
          <h1 class="text-5xl">200 +</h1>
          <p>HAPPY CLIENTS</p>
        </div>
        <div
          class="bg-gradient-to-tr from-slate-200 to-white py-5 rounded-xl shadow-xl"
          style="font-family: 'Bentham', serif"
        >
          <h1 class="text-5xl">1,000 +</h1>
          <p>HOURS OF WORK</p>
        </div>
        <div></div>
      </div>

      <div class="mt-8">
        <a
          href="#"
          class="bg-blue-500 text-white hover:bg-blue-600 py-2 px-6 rounded-full text-lg font-semibold transition duration-300 ease-in-out"
          >You Can Hire Me</a
        >
      </div>
    </div>

    <!-- Back to top Button -->
    <div class="fixed bottom-10 right-10">
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
  </section>

  <!-- Services What I do -->
  <section
    id="services"
    class="py-10 bg-[url('https://plus.unsplash.com/premium_photo-1674729243673-0b5e871a8a24?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1535&q=80')] bg-cover bg-center bg-no-repeat"
  >
    <div class="w-4/5 mx-auto">
      <h1
        class="text-4xl md:text-[50px] font-bold text-center"
        style="font-family: 'Bentham', serif"
      >
        What I Do
      </h1>

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

  <!-- Skill Section -->
  <section id="skills" class="py-10" style="font-family: 'Bentham', serif">
    <div class="w-4/5 mx-auto">
      <h1 class="text-4xl md:text-[50px] font-bold text-center">My Skills</h1>

      <div class="h-1 w-52 bg-gray-600 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-10 mt-8">
        <div>
          <div class="flex space-x-2 text-3xl items-center font-bold">
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
                d="M4.5 12a7.5 7.5 0 0015 0m-15 0a7.5 7.5 0 1115 0m-15 0H3m16.5 0H21m-1.5 0H12m-8.457 3.077l1.41-.513m14.095-5.13l1.41-.513M5.106 17.785l1.15-.964m11.49-9.642l1.149-.964M7.501 19.795l.75-1.3m7.5-12.99l.75-1.3m-6.063 16.658l.26-1.477m2.605-14.772l.26-1.477m0 17.726l-.26-1.477M10.698 4.614l-.26-1.477M16.5 19.794l-.75-1.299M7.5 4.205L12 12m6.894 5.785l-1.149-.964M6.256 7.178l-1.15-.964m15.352 8.864l-1.41-.513M4.954 9.435l-1.41-.514M12.002 12l-3.75 6.495"
              />
            </svg>

            <h2 class="">Development</h2>
          </div>

          <div class="grid grid-cols-2 md:grid-cols-3 gap-5 mt-5">
            <div
              class="h-40 w-40 flex items-center justify-center rounded-full font-bold"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #e3e9ed 0%,
                  #fff 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <span>HTML</span>
            </div>
            <div
              class="h-40 w-40 flex items-center justify-center rounded-full font-bold"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #e3e9ed 0%,
                  #fff 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <span>CSS</span>
            </div>
            <div
              class="h-40 w-40 flex items-center justify-center rounded-full font-bold"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #e3e9ed 0%,
                  #fff 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <span>TAILWIND CSS</span>
            </div>
            <div
              class="h-40 w-40 flex items-center justify-center rounded-full font-bold"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #e3e9ed 0%,
                  #fff 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <span>JAVASCRIPT</span>
            </div>
            <div
              class="h-40 w-40 flex items-center justify-center rounded-full font-bold"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #e3e9ed 0%,
                  #fff 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <span>LARAVEL</span>
            </div>
            <div
              class="h-40 w-40 flex items-center justify-center rounded-full font-bold"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #e3e9ed 0%,
                  #fff 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <span>VUE</span>
            </div>
          </div>
        </div>
        <div class="">
          <div class="flex justify-around">
            <div class="">
              <div
                class="flex space-x-2 text-3xl items-center font-bold"
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
                    d="M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.496-3.03c.317-.384.74-.626 1.208-.766M11.42 15.17l-4.655 5.653a2.548 2.548 0 11-3.586-3.586l6.837-5.63m5.108-.233c.55-.164 1.163-.188 1.743-.14a4.5 4.5 0 004.486-6.336l-3.276 3.277a3.004 3.004 0 01-2.25-2.25l3.276-3.276a4.5 4.5 0 00-6.336 4.486c.091 1.076-.071 2.264-.904 2.95l-.102.085m-1.745 1.437L5.909 7.5H4.5L2.25 3.75l1.5-1.5L7.5 4.5v1.409l4.26 4.26m-1.745 1.437l1.745-1.437m6.615 8.206L15.75 15.75M4.867 19.125h.008v.008h-.008v-.008z"
                  />
                </svg>

                <h1>Tools</h1>
              </div>

              <ul class="mt-5 text-xl">
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span> Git + Github</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>Command Line</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>Chrome DevTools</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>Grunt + Gulp</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>Postman</span>
                </li>
              </ul>
            </div>

            <div class="">
              <div class="flex space-x-2 text-3xl items-center font-bold">
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
                    d="M12 18v-5.25m0 0a6.01 6.01 0 001.5-.189m-1.5.189a6.01 6.01 0 01-1.5-.189m3.75 7.478a12.06 12.06 0 01-4.5 0m3.75 2.383a14.406 14.406 0 01-3 0M14.25 18v-.192c0-.983.658-1.823 1.508-2.316a7.5 7.5 0 10-7.517 0c.85.493 1.509 1.333 1.509 2.316V18"
                  />
                </svg>

                <h1>KNOWLEDGE</h1>
              </div>

              <ul class="mt-5 text-xl">
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>CSS Detangling</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>ECMAScript 6</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>Usability</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>SEO</span>
                </li>
                <li class="flex">
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
                      d="M4.5 12.75l6 6 9-13.5"
                    />
                  </svg>

                  <span>TDD</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Work Example -->
  <section id="workExample" class="bg-gray-50">
    <div class="w-4/5 mx-auto py-10">
      <h1
        class="text-4xl md:text-[50px] font-bold text-center"
        style="font-family: 'Bentham', serif"
      >
        Some of My Work
      </h1>
      <div class="h-1 w-52 bg-gray-600 mx-auto rounded-full my-3"></div>

      <div
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
            src="./assets/Home-Real-Fruit.png"
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
            src="./assets/Home-Real-Fruit.png"
          />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>

        <a
          href="#"
          class="carousel-cell mx-5 bg-gradient-to-tr from-slate-200 to-white p-4 rounded-2xl shadow"
          style="font-family: 'Bentham', serif"
        >
          <img class="h-72 w-[500px] rounded" src="./assets/wb-1.jpg" />
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
            src="./assets/Home-Real-Fruit.png"
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
            src="./assets/Home-Real-Fruit.png"
          />
          <h1 class="text-2xl mt-2">Responsive design development</h1>
          <p class="text-xl">Using Bootstarp</p>
        </a>
      </div>
    </div>
  </section>

  <!-- Client Experience -->
  <section id="clientExperience">
    <div class="w-4/5 mx-auto py-10 text-center col-span-full">
      <h1
        class="text-4xl md:text-[50px] font-bold flex flex-col"
        style="font-family: 'Bentham', serif"
      >
        My Client Experience
      </h1>

      <div class="h-1 w-52 bg-slate-400 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10">
        <div
          class="border bg-gradient-to-tr from-slate-200 to-white p-5 rounded-xl shadow-lg shadow-slate-300"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-28 w-28 rounded-full mx-auto"
            src="./assets/arif001-Recovered.png"
            alt=""
          />
          <h1 class="text-4xl">Arif Hosen</h1>
          <p class="">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            minus nihil doloremque. Incidunt accusamus magni, velit non quisquam
            nesciunt tenetur?
          </p>
        </div>

        <div
          class="border bg-gradient-to-tr from-slate-200 to-white p-5 rounded-xl shadow-lg shadow-slate-300"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-28 w-28 rounded-full mx-auto"
            src="./assets/arif001-Recovered.png"
            alt=""
          />
          <h1 class="text-4xl">Arif Hosen</h1>
          <p class="">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            minus nihil doloremque. Incidunt accusamus magni, velit non quisquam
            nesciunt tenetur?
          </p>
        </div>

        <div
          class="border bg-gradient-to-tr from-slate-200 to-white p-5 rounded-xl shadow-lg shadow-slate-300"
          style="font-family: 'Bentham', serif"
        >
          <img
            class="h-28 w-28 rounded-full mx-auto"
            src="./assets/arif001-Recovered.png"
            alt=""
          />
          <h1 class="text-4xl">Arif Hosen</h1>
          <p class="">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            minus nihil doloremque. Incidunt accusamus magni, velit non quisquam
            nesciunt tenetur?
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact section -->
  <section
    id="contact"
    class="pt-5 md:py-10 bg-cover bg-center bg-no-repeat"
    style="
      font-family: 'Bentham', serif;
      background-image: url('https://images.unsplash.com/photo-1528747045269-390fe33c19f2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
    "
  >
    <div class="w-full md:w-4/5 mx-auto text-white">
      <h1 class="text-4xl md:text-[50px] font-bold text-center">
        Connect with me
      </h1>
      <p class="text-center">
        Have a sweet project in mind or just want to say hi? <br />
        Feel free to send me a message!
      </p>

      <div class="h-1 w-52 bg-gray-200 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-0 p-5 md:gap-10 my-5">
        <div class="col-span-2">
          <div class="px-4 mx-auto max-w-screen-md">
            <form action="#" class="space-y-8">
              <div>
                <label
                  for="name"
                  class="block mb-1 text-lg font-medium text-gray-100"
                  >Your Name</label
                >
                <input
                  type="text"
                  id="name"
                  class="shadow-sm bg-transparent border-b transition transform ease-in-out delay-150 text-lg focus-visible:outline-none block w-full p-1"
                  required
                />
              </div>
              <div>
                <label
                  for="email"
                  class="block mb-1 text-lg font-medium text-gray-100"
                  >Your email</label
                >
                <input
                  type="email"
                  id="email"
                  class="shadow-sm bg-transparent border-b transition transform ease-in-out delay-150 text-lg focus-visible:outline-none block w-full p-1"
                  required
                />
              </div>
              <div>
                <label
                  for="subject"
                  class="block mb-1 text-lg font-medium text-gray-100"
                  >Your Subject</label
                >
                <input
                  type="text"
                  id="subject"
                  class="shadow-sm bg-transparent border-b transition transform ease-in-out delay-150 text-lg focus-visible:outline-none block w-full p-1"
                  required
                />
              </div>
              <div class="sm:col-span-2">
                <label
                  for="message"
                  class="block mb-1 text-lg font-medium text-gray-100"
                  >Your Message</label
                >
                <textarea
                  id="message"
                  rows="5"
                  class="shadow-sm bg-transparent border-b transition transform ease-in-out delay-150 text-lg focus-visible:outline-none block w-full p-1"
                ></textarea>
              </div>
              <button
                type="submit"
                class="py-3 px-5 text-lg text-center text-black font-bold rounded-lg bg-gradient-to-tr from-slate-500 to-white transition duration-300 ease-in hover:scale-110"
              >
                Send message
              </button>
            </form>
          </div>
        </div>

        <div class="bg-[#99aec2] p-5 mt-5 rounded-xl col-span-1">
          <img src="./assets/contact.jpg" alt="" />

          <h2 class="text-3xl font-bold text-center mt-5">
            You Can Touch With
          </h2>
          <div class="grid grid-cols-4 md:grid-cols-3 gap-5 py-5">
            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="black"
                class="w-8 h-8"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"
                />
              </svg>
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/facebook.svg" alt="" />
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/twitter.svg" alt="" />
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/linkedin.svg" alt="" />
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/github.svg" alt="" />
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/skype.svg" alt="" />
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/upwork.svg" alt="" />
            </a>

            <a
              href="#"
              class="h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110"
              style="
                box-shadow: 8px 8px 10px 0px #dee5ec;
                background-image: linear-gradient(
                  145deg,
                  #90c9ee 0%,
                  #8f959a 100%
                );
                font-family: 'Bentham', serif;
                font-size: 20px;
              "
            >
              <img class="h-8" src="./assets/youtube.svg" alt="" />
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer id="footer" class="bg-[#99aec2] italic py-4">
    <div class="text-center">
      <p>&copy; 2023 Arif Hosen - All Rights Reserved</p>
    </div>
  </footer>
</template>

<style scoped>
#dot-nav {
  position: fixed;
  right: 34px;
  z-index: 1;
  top: 50%;
  bottom: auto;
  transform: translateY(-50%);
  visibility: hidden;
  opacity: 0;
  transition: visibility 0s, opacity 0.5s ease;
}

#dot-nav.active {
  visibility: visible;
  opacity: 1;
  transition: visibility 0s, opacity 0.5s ease;
}

@media only screen and (max-width: 768px) {
  #dot-nav {
    display: none;
  }
}

#dot-nav .dot-container {
  text-align: right;
}

#dot-nav a {
  display: inline-block;
  -webkit-backface-visibility: hidden;
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

#dot-nav a:focus span,
#dot-nav a:hover span {
  transform: scale(0.75);
}

#dot-nav a:focus .dot-label,
#dot-nav a:hover .dot-label {
  opacity: 1;
}

#dot-nav a.is-selected .dot {
  background-color: #000;
}

#dot-nav .dot {
  position: relative;
  top: 7px;
  height: 20px;
  width: 20px;
  border-radius: 50%;
  background: red;
  transition: transform 0.2s, background-color 0.5s;
  transform-origin: 50% 50%;
}

#dot-nav .dot-label {
  position: relative;
  top: 3px;
  padding: 0.4em 0.5em;
  color: #000;
  font-family: Gotham, Helvetica, Arial, sans-serif;
  font-size: 1em;
  font-weight: 500;
  text-transform: uppercase;
  opacity: 0;
  transition: transform 0.2s, opacity 0.2s;
  transform-origin: 100% 50%;
}
</style>
