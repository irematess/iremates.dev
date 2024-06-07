<!-- eslint-disable vue/multi-word-component-names -->
<script setup>
import { useDark, useToggle } from '@vueuse/core'
const isDark = useDark()
const toggleDark = useToggle(isDark)
</script>
<template>
  <div
    class="max-lg:w-4/5 w-1/2 mx-auto bg-gradient-to-t from-pink-50 to-pink-100 dark:from-zinc-800 dark:to-zinc-900 flex justify-between items-center max-sm:px-3 px-4 py-3 rounded-lg border-[1px] dark:border-zinc-800 border-pink-100"
  >
    <!-- Navbar -->
    <div
      class="flex items-center max-sm:gap-2 gap-8 text-pink-300 dark:text-white max-sm:text-xl text-2xl"
    >
      <router-link to="/"
        ><i
          class="fa-solid fa-house rounded-lg p-2 hover:bg-pink-200 dark:hover:bg-zinc-600 hover:text-white ease-linear duration-500"
        ></i
      ></router-link>
      <a href="iremates.pdf" download>CV</a>
      <router-link to="/"
        ><i
          class="fa-regular fa-file rounded-lg p-2 hover:bg-pink-200 dark:hover:bg-zinc-600 hover:text-white ease-linear duration-500"
        ></i
      ></router-link>
      <router-link to="/projects"
        ><i
          class="fa-solid fa-laptop rounded-lg p-2 hover:bg-pink-200 dark:hover:bg-zinc-600 hover:text-white ease-linear duration-500"
        ></i
      ></router-link>
    </div>
    <!-- Light/Dark -->
    <button @click="toggleDark()">
      <i
        :class="{
          'fa-solid fa-moon text-white': isDark,
          'fa-solid fa-sun text-pink-300': !isDark
        }"
        class="text-2xl max-sm:text-xl"
      ></i>
    </button>
  </div>
</template>
