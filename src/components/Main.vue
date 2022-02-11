<template>
  <!-- Main Area -->
  <main>
    <!-- Hero -->
    <div
      class="relative pt-16 pb-32 flex content-center items-center justify-center"
      style="min-height: 95vh"
    >
      <div
        class="rounded-xl absolute top-0 w-full h-full bg-top bg-cover"
        style="
          background-image: url('https://images.unsplash.com/photo-1491895200222-0fc4a4c35e18?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2148&q=80');
        "
      >
        <span
          id="blackOverlay"
          class="w-screen h-full absolute  border-box"
        />
      </div>
      <div class="container relative mx-auto" data-aos="fade-in">
        <div class="items-center flex flex-wrap">
          <div id="name" class="w-full lg:w-full px-4 ml-auto mr-auto text-center">
            <div>
              <h1 id="j" class=" font-semibold text-8xl text-shadow-xl">
                J <span class="parker">Parker</span>
              </h1>
              <p class="p-2 mt-5 text-2xl text-shadow-xl">
                Fully responsive and extremely fast modern applications and web pages tailor made for each customers needs and wants
              </p>

              <a
                id="learn"
                href="#"
                class="shadow-2xl text-shadow-2xl nter bg-transparent hover:bg-cyan-500 text-cyan-600 font-bold hover:text-white p-4 border border-gray-500 hover:border-transparent rounded inline-block mt-5 cursor-pointer hover:translate-y-5 active:translate-y-5"
              >Enhance</a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
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
    </div>

    <!-- About Section -->
    <section id="about" class="relative py-20 bg-black text-white">
      <div class="container mx-auto px-4">
        <div class="items-center flex flex-wrap">
          <div
            class="w-full md:w-4/12 ml-auto mr-auto px-4"
            data-aos="fade-right"
          >
            <img
              alt="..."
              class="max-w-full rounded-lg shadow-lg opacity-50"
              src="https://images.unsplash.com/photo-1603969280040-3bbb77278211?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
            >
          </div>
          <div
            class="w-full md:w-5/12 ml-auto mr-auto px-4"
            data-aos="fade-left"
          >
            <div class="md:pr-12">
              <small class="lato text-cyan-100">About my work</small>
              <h3 class="com text-cyan-400 text-4xl uppercase font-bold">
                Full Stack
              </h3>

              <ul class="list-none mt-6">
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="font-semibold inline-block py-3 mr-3 text-orange-500"
                      ><i class="fas fa-dumbbell fa-2x" /></span>
                    </div>
                    <div>
                      <h4 class="lato text-gray-300 text-xl">
                        From custom tailored designs to full production deployment
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="font-semibold inline-block py-3 mr-3 text-orange-500"
                      ><i class="fas fa-hard-hat fa-2x" /></span>
                    </div>
                    <div>
                      <h4 class="lato text-xl">
                        Vue/Vite applications and web sites that run extremely fast
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="font-semibold inline-block py-3 mr-3 text-orange-500"
                      ><i class="fas fa-users fa-2x" /></span>
                    </div>
                    <div>
                      <h4 class="lato text-xl">
                        Systems integrations including Crestron, Qsys, Dante, Control4, BrightSign
                      </h4>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!--Section -->
    <section class="pt-20 pb-48">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center text-center mb-24">
          <div class="w-full lg:w-6/12 px-4">
            <h2 class="text-shadow-xl com text-cyan-500 text-6xl font-semibold uppercase">
              Demo Projects
            </h2>
            <p class="text-lg text-gray-300 leading-relaxed m-4 lato">
              Some test projects to give some examples and ideas for customers
            </p>
          </div>
        </div>
        <!-- Card Wrapper -->
        <div class="flex flex-wrap">
          <!-- Card 1 -->
          <div
            class="w-full md:w-4/12 lg:mb-0 mb-12 px-4"
            data-aos="flip-right"
          >
            <div class="px-6">
              <img
                id="learn"
                alt="..."
                src="https://images.unsplash.com/photo-1589185810360-8ea760bb9836?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
                class="shadow-lg rounded max-w-full mx-auto"
                style="max-width: 250px"
              >
              <div id="learn" class="pt-6 text-center">
                <a href="https://monsteria-vite.netlify.app/"><h5 class="text-xl text-emerald-500 font-bold">Monsteria</h5></a>
                <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                  Mobile First Plant app
                </p>
              </div>
            </div>
          </div>
          <!-- Card 2 -->
          <div
            class="w-full md:w-4/12 lg:mb-0 mb-12 px-4"
            data-aos="flip-right"
          >
            <div class="px-6">
              <img
                id="learn"
                alt="..."
                src="https://images.unsplash.com/flagged/photo-1587302164675-820fe61bbd55?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=580&q=80"
                class="shadow-lg rounded max-w-full mx-auto"
                style="max-width: 250px"
              >
              <div id="learn" class="pt-6 text-center">
                <a href="https://vue-grocery-f79c2.web.app/"><h5 class="text-xl text-yellow-300 font-bold">Grocery List App</h5></a>
                <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                  Tied to a backend database to handle grocery items
                </p>
              </div>
            </div>
          </div>
          <!-- Card 3 -->
          <div
            class="w-full md:w-4/12 lg:mb-0 mb-12 px-4"
            data-aos="flip-right"
          >
            <div class="px-6">
              <img
                id="learn"
                alt="..."
                src="https://icon-library.com/images/github-icon-white/github-icon-white-2.jpg"
                class="shadow-lg rounded max-w-full mx-auto"
                style="max-width: 250px"
              >
              <div id="learn" class="pt-6 text-center">
                <h5 class="text-xl text-cyan-600 font-bold">
                  GitHub Repos
                </h5>
                <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                  lots of projects in my public repositories
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<style>

#learn:hover {
 transition: all .5s ease-in-out;
 transform: translateY(-5px);
}
#learn:active {
transition: all .1s ease-in-out;
 transform: translateY(5px);
 opacity: 0.5;
}
h1 {
  font-family: 'Comforter', cursive;
}
.com {
  font-family: 'Comforter', cursive;
}
#j {
  color: black;
}
.parker {
  color: black;
}
</style>
