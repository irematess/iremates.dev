<!-- eslint-disable vue/multi-word-component-names -->
<script setup></script>
<template>
  <div class="w-1/2 mx-auto flex justify-between px-4 py-3 bg-white box rounded-lg items-center">
    <div class="flex gap-8 text-primary">
      <router-link to="/"
        ><i
          class="fa-solid fa-house p-2 border-[1px] border-primary rounded-lg box hover:bg-pink-200 hover:border-0 mb-2 transition-all duration-300 hover:translate-x-1"
        ></i
      ></router-link>
      <router-link to="/"
        ><i
          class="fa-regular fa-file p-2 border-[1px] border-primary rounded-lg box hover:bg-pink-200 hover:border-0 hover:text-white"
        ></i
      ></router-link>
      <router-link to="/projects"
        ><i
          class="fa-solid fa-laptop p-2 border-[1px] border-primary rounded-lg box-border hover:bg-pink-200 hover:border-0 hover:text-white"
        ></i
      ></router-link>
    </div>
    <div class="text-xl gap-4 flex">
      <button><i class="fa-solid fa-moon text-gray-400 box"></i></button>
      <button><i class="fa-solid fa-sun text-pink-300 box"></i></button>
    </div>
  </div>
</template>
