<template>
  <section class="pb-20 relative block bg-black text-white">
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 80px; transform: translateZ(0px)"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon points="2560 0 2560 100 0 100" />
      </svg>
    </div>
    <div class="container mx-auto px-4 lg:pt-24 lg:pb-64 pb-20 pt-20">
      <div class="flex flex-wrap text-center justify-center">
        <div class="w-full lg:w-6/12 px-4">
          <h2 class="com text-6xl font-semibold text-white uppercase">
            Contact Us
          </h2>
          <p class="text-lg leading-relaxed mt-4 mb-4">
            Contact us to ask any questions
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="relative block py-24 lg:pt-0 bg-black">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
        <div class="w-full lg:w-6/12 px-4">
          <div
            class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300"
            data-aos="fade-up-right"
          >
            <div class="flex-auto p-5 lg:p-10 bg-cyan-500 text-white">
              <h4 class="lato text-2xl font-semibold">
                Want to work with us?
              </h4>
              <p class="lato leading-relaxed mt-1 mb-4">
                Complete this form and we will get back to you in 24 hours.
              </p>
              <form
                action="https://formkeep.com/f/fa0e7350ff41"
                accept-charset="UTF-8"
                enctype="multipart/form-data"
                method="POST"
              >
                <div class="relative w-full mb-3 mt-8">
                  <label
                    class="block uppercase text-xs font-bold mb-2"
                    for="full-name"
                  >Full Name</label><input

                    type="text"
                    class="px-3 py-3 placeholder-gray-800 text-gray-500 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                    placeholder="Full Name"
                    style="transition: all 0.15s ease 0s"
                  >
                </div>
                <div class="relative w-full mb-3">
                  <label
                    class="block uppercase text-xs font-bold mb-2"
                    for="email"
                  >Email</label><input

                    type="email"
                    class="px-3 py-3 placeholder-gray-800 text-gray-500 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                    placeholder="Email"
                    style="transition: all 0.15s ease 0s"
                  >
                </div>
                <div class="relative w-full mb-3">
                  <label
                    class="block uppercase text-xs font-bold mb-2"
                    for="message"
                  >Message</label><textarea

                    rows="4"
                    cols="80"
                    class="px-3 py-3 placeholder-gray-800 bg-white text-gray-500 rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                    placeholder="Type a message..."
                  />
                </div>
                <div class="text-center mt-6">
                  <button
                    id="learn"
                    class="bg-transparent hover:bg-lime-400 hover:text-cyan-800 text-white font-semibold hover:text-white p-4 border border-gray-500 hover:border-transparent rounded inline-block mt-5 cursor-pointer active:translate-y-5"
                    style="transition: all 0.15s ease 0s"
                  >
                    Send Message
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// import { getDatabase, ref, set } from 'firebase/database'
//
// const db = getDatabase()
// set(ref(db, 'Forms'), {
//   name: '',
//   email: '',
//   text: '',
// })
//   .then(() => {
//   // Data saved successfully!
//   })
//   .catch((_error) => {
//   // The write failed...
//     return { name, email, text }
//   })

</script>
