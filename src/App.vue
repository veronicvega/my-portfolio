<template >
  <div class="bg-[#111827] min-h-screen">
    <navBar/>
    <HeroSection/>

  </div>
</template>

<script setup>
import { defineAsyncComponent } from 'vue';
const navBar = defineAsyncComponent(() => import('@components/NavBar.vue'));
const HeroSection = defineAsyncComponent(() => import('@components/HeroSection.vue'));



</script>