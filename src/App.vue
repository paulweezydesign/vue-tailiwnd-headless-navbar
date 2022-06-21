<template>
  <nav class="grid grid-cols-2 w-[100vw] items-center px-[8%]">
    <div class="">
      <h1 class="text-black/90 text-xl font-black">Vue App</h1>
    </div>
    <div class="flex justify-end">
      <Sidebar />
    </div>
  </nav>
</template>

<script setup>
import Sidebar from './components/Sidebar.vue';
</script>
