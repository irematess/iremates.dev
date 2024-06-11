<script setup></script>
<template>
  <div
    class="max-lg:w-4/5 w-1/2 mx-auto bg-gradient-to-t from-pink-50 to-pink-100 dark:from-zinc-800 dark:to-zinc-900 flex flex-col items-center justify-center dark:bg-black rounded-lg border-[1px] border-pink-100 dark:border-zinc-800"
  >
    <!-- About -->
    <div
      class="w-full flex max-lg:flex-col flex-row items-center justify-center pt-10 pb-5 px-8 max-sm:px-4"
    >
      <!-- Bio -->
      <div class="flex flex-col gap-4 px-10 max-sm:px-8">
        <!-- Title -->
        <span class="text-yellow-500 max-sm:text-xl text-3xl font-semibold"
          >{
          <span class="text-yellow-500"
            >{ <span class="text-black dark:text-white">FRONTEND DEVELOPER </span> } </span
          >}</span
        >
        <div class="italic max-sm:text-md text-xl px-2 dark:text-white">
          Hello, I am studying computer programming at Uludağ University. I'm a frontend developer.
          I really enjoy writing JavaScript. I am currently developing projects with Vue.js.
        </div>
      </div>
      <figure class="w-[55rem] md:w-[35rem] max-sm:w-full sm:w-full flex items-center">
        <img src="../assets/profile.png" alt="" />
      </figure>
    </div>
    <!-- Tecnologies -->
    <div
      class="w-full flex flex-col gap-4 items-center py-6 border-t-2 border-white dark:border-zinc-800"
    >
      <span class="text-2xl font-semibold px-4 dark:text-white">Technologie</span>
      <div class="flex gap-4 items-center px-2">
        <img src="../assets/html-logo.png" alt="" class="max-sm:w-6 max-sm:h-6 w-16 h-16" />
        <img src="../assets/css.webp" alt="" class="max-sm:w-6 max-sm:h-6 w-12 h-12" />
        <img src="../assets/bootstrap.png" alt="" class="max-sm:w-6 max-sm:h-6 h-12" />
        <img src="../assets/tailwind.png" alt="" class="max-sm:w-6 max-sm:h-6 h-12" />
        <img src="../assets/javascript.png" alt="" class="max-sm:w-6 max-sm:h-6 h-16" />
        <img src="../assets/vue.webp" alt="" class="max-sm:w-6 max-sm:h-6 h-12" />
      </div>
    </div>
  </div>
</template>
