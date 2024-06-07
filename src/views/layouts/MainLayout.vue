<script setup>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
</script>
<template>
  <div class="py-28 flex flex-col gap-16">
    <Header />
    <RouterView />
    <Footer />
  </div>
</template>
<style></style>
