<script setup>
import Heading from "./Heading.vue";

const lable = "block mb-1 text-lg font-medium text-gray-100";

const inputTextarea =
  "shadow-[1.0px_2.0px_2.0px_#99aec2] bg-transparent border-b text-2xl focus-visible:outline-none focus-visible:bg-[#beccd8] focus-visible:bg-opacity-30 block w-full p-2";

const conSocialIcon =
  "h-14 w-14 flex items-center justify-center rounded-full transition ease-in-out delay-150 duration-300 hover:-translate-y-1 hover:scale-110";
</script>
<template>
  <section
    id="contact"
    class="pt-5 md:py-10 bg-gradient-to-r from-indigo-500 to-purple-500 bg-cover bg-center bg-no-repeat"
    style="
      font-family: 'Bentham', serif;
      /* background-image: url('https://images.unsplash.com/photo-1554034483-04fda0d3507b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80'); */
    "
  >
    <div class="w-full md:w-4/5 mx-auto text-center">
      <Heading>Connect with me</Heading>
      <p class="font-serif text-center">
        Have a sweet project in mind or just want to say hi? <br />
        Feel free to send me a message!
      </p>

      <div class="h-1 w-52 bg-gray-200 mx-auto rounded-full my-3"></div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-0 p-5 md:gap-10 my-5">
        <div class="col-span-2">
          <div class="px-4 mx-auto max-w-screen-md">
            <form action="#" class="text-black space-y-8 text-left">
              <div>
                <label for="name" :class="lable">Your Name</label>
                <input type="text" id="name" :class="inputTextarea" required />
              </div>
              <div>
                <label for="email" :class="lable">Your email</label>
                <input
                  type="email"
                  id="email"
                  :class="inputTextarea"
                  required
                />
              </div>
              <div>
                <label for="subject" :class="lable">Your Subject</label>
                <input
                  type="text"
                  id="subject"
                  :class="inputTextarea"
                  required
                />
              </div>
              <div class="sm:col-span-2">
                <label for="message" :class="lable">Your Message</label>
                <textarea
                  id="message"
                  rows="5"
                  :class="inputTextarea"
                ></textarea>
              </div>
              <button
                type="submit"
                class="py-3 px-5 text-lg text-center text-black font-bold rounded-lg bg-gradient-to-tr from-slate-500 to-white transition duration-300 ease-in hover:scale-110 shadow-2xl"
              >
                Send message
              </button>
            </form>
          </div>
        </div>

        <div class="bg-[#99aec2] p-5 mt-5 rounded-xl col-span-1 shadow-2xl">
          <img src="../assets/contact.jpg" alt="" />

          <h2 class="text-3xl font-bold text-center mt-5">
            You Can Touch With
          </h2>
          <div class="grid grid-cols-4 md:grid-cols-3 gap-5 py-5">
            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/email.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/facebook.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/twitter.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/linkedin.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/github.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/skype.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/upwork.svg" alt="" />
            </a>

            <a href="#" :class="conSocialIcon" class="socialIcon">
              <img class="h-8" src="../assets/youtube.svg" alt="" />
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.socialIcon {
  box-shadow: 8px 8px 10px 0px #dee5ec;
  background-image: linear-gradient(145deg, #90c9ee 0%, #8f959a 100%);
  font-family: "Bentham", serif;
}
</style>
