<script setup>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
</script>
<template>
  <div class="w-full h-full py-28 flex flex-col items-center gap-16">
    <Header />
    <RouterView />
    <Footer />
  </div>
</template>
