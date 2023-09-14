<script setup>
import Heading from "./Heading.vue";

const inputTextarea =
  "shadow-[1.0px_2.0px_2.0px_#99aec2] bg-transparent border-b text-lg focus-visible:outline-none block w-full p-1";
</script>
<template>
  <section
    id="contact"
    class="pt-5 md:py-10 bg-cover bg-center bg-no-repeat"
    style="
      font-family: 'Bentham', serif;
      background-image: url('https://images.unsplash.com/photo-1528747045269-390fe33c19f2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
    "
  >
    <div class="w-full md:w-4/5 mx-auto text-center text-white">
      <Heading>Connect with me</Heading>
      <p class="text-center">
        Have a sweet project in mind or just want to say hi? <br />
        Feel free to send me a message!
      </p>

      <div class="h-1 w-52 bg-gray-200 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-0 p-5 md:gap-10 my-5">
        <div class="col-span-2">
          <div class="px-4 mx-auto max-w-screen-md">
            <form action="#" class="space-y-8 text-left">
              <div>
                <label
                  for="name"
                  class="block mb-1 text-lg font-medium text-gray-100"
                  >Your Name</label
                >
                <input type="text" id="name" :class="inputTextarea" required />
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
                  :class="inputTextarea"
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
                  :class="inputTextarea"
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
                  :class="inputTextarea"
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
          <img src="../assets/contact.jpg" alt="" />

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
              <img class="h-8" src="../assets/facebook.svg" alt="" />
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
              <img class="h-8" src="../assets/twitter.svg" alt="" />
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
              <img class="h-8" src="../assets/linkedin.svg" alt="" />
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
              <img class="h-8" src="../assets/github.svg" alt="" />
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
              <img class="h-8" src="../assets/skype.svg" alt="" />
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
              <img class="h-8" src="../assets/upwork.svg" alt="" />
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
              <img class="h-8" src="../assets/youtube.svg" alt="" />
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
