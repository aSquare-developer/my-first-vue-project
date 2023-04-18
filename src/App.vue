<script setup>
import { RouterView } from 'vue-router'
import Header from "@/components/Header.vue";
</script>

<template>

  <Header />

  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="mx-auto max-w-7xl py-5 bg-gray-300">
      <RouterView />
    </div>
  </div>

</template>