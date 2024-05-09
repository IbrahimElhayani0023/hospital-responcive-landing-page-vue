<template>
  <div class="bg-cyan-700 h-screen pt-16 lg:pt-0">
    <div
      class="container flex flex-col lg:flex-row justify-between items-center h-full"
    >
      <div>
        <h2 class="text-cyan-100 text-center lg:text-left ps-4 mb-4">
          welcome to my hospital demo <span class="hidden lg:inline">>></span>
        </h2>
        <h3
          class="text-cyan-50 lg:text-7xl text-4xl font-bold text-center lg:text-left font-sans mb-4"
        >
          Find Your Best Doctor
        </h3>
        <form
          class="bg-cyan-50 px-4 py-2 w-[400px] rounded mt-8 ms-4 shadow-xl lg:mt-0"
        >
          <label
            class="text-cyan-600 font-bold uppercase block border-b-2 border-gray-200 mb-2 text-center"
            >search</label
          >
          <div>
            <input
              type="text"
              placeholder="find your doctor"
              class="ps-1 bg-cyan-50 text-cyan-600 border-b-2 border-cyan-800 outline-none w-full mt-3"
            />
            <button
              class="bg-cyan-600 hover:bg-cyan-950 duration-200 text-cyan-50 px-6 py-3 rounded-md mt-5 mb-2 w-full"
            >
              search
            </button>
          </div>
        </form>
      </div>
      <div class="lg:mt-0">
        <img
          class="w-[300px] md:w-[400px] lg:w-full"
          src="../assets/img/banner-hero.png"
          alt=""
        />
      </div>
    </div>
  </div>
</template>


