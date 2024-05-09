<template>
  <nav class="fixed top-0 left-0 right-0 px-5">
    <div class="container flex items-center justify-between">
      <a href="#" class="">
        <img src="../assets/img/logo.svg" width="136" height="46" alt="logo" />
      </a>
      <ul
        :class="
          'duration-300 flex gap-7 flex-col fixed top-0 right-0 p-5 w-[260px] h-screen bg-cyan-950 lg:flex-row lg:relative lg:p-0 lg:h-auto lg:translate-x-0 lg:bg-transparent' +
          (isActive ? ' translate-x-0' : ' translate-x-[100%]')
        "
      >
        <li class="block lg:hidden">
          <button @click="isActive = !isActive">delete</button>
        </li>
        <li class="block lg:hidden">
          <img src="../assets/img/logo.svg" alt="logo" />
        </li>

        <li><a class="hover:text-cyan-400 text-cyan-100" href="#">Home</a></li>
        <li>
          <a class="hover:text-cyan-400 text-cyan-100" href="#">Doctors</a>
        </li>
        <li>
          <a class="hover:text-cyan-400 text-cyan-100" href="#">Service</a>
        </li>
        <li><a class="hover:text-cyan-400 text-cyan-100" href="#">Blogs</a></li>
        <li>
          <a class="hover:text-cyan-400 text-cyan-100" href="#">Contact</a>
        </li>
      </ul>
      <div class="flex gap-5 items-center">
        <button
          @click="isActive = !isActive"
          :class="
            'lg:hidden text-cyan-100 px-3 py-1' +
            (isActive ? ' hidden' : ' block')
          "
        >
          menu
        </button>
        <a
          href="#"
          class="bg-cyan-500 hover:bg-cyan-900 duration-200 text-white px-5 py-2 rounded"
          >Login</a
        >
      </div>
    </div>
  </nav>
</template>

<script setup lang="ts">
import { ref } from "vue";
const isActive = ref(false);
</script>