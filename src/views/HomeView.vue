<script setup></script>
<template>
  <div class="flex flex-col gap-16">
    <div class="w-1/2 mx-auto bg-white box flex justify-between py-10 px-8 rounded-lg items-center">
      <div class="flex flex-col gap-4 px-10">
        <span class="text-yellow-500 text-3xl font-semibold"
          >{
          <span class="text-yellow-500"
            >{ <span class="text-black">FRONTEND DEVELOPER </span> } </span
          >}</span
        >
        <div class="italic text-xl px-2">
          Hello, I am studying computer programming at Uludağ University. I'm a frontend developer.
          I really enjoy writing JavaScript. I am currently developing projects with Vue.js.
        </div>
      </div>

      <figure class="w-[55rem]">
        <img src="../assets/profile.png" alt="" />
      </figure>
    </div>
    <div class="w-1/2 mx-auto bg-white box py-8 flex flex-col items-center gap-4 rounded-lg">
      <span class="text-2xl font-semibold px-4">Tecnologies</span>
      <div class="flex gap-4 items-center px-2">
        <img src="../assets/html-logo.png" alt="" class="w-16 h-16" />
        <img src="../assets/css.webp" alt="" class="w-12 h-12" />
        <img src="../assets/bootstrap.png" alt="" class="h-12" />
        <img src="../assets/tailwind.png" alt="" class="h-12" />
        <img src="../assets/javascript.png" alt="" class="h-16" />
        <img src="../assets/vue.webp" alt="" class="h-12" />
      </div>
    </div>
  </div>
</template>
