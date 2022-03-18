<script setup lang="ts">
import Logo from "./Logo.vue";
import NavBar from "./NavBar.vue";
</script>
<template>
  <header
    class="bg-white w-full flex items-center justify-between p-5 shadow-lg sticky top-0"
  >
    <div class="flex items-center">
      <Logo />
      <p class="ml-1">
        Buisness<span class="text-[#FF0000] font-semibold">'sync</span>
      </p>
    </div>
    <NavBar />
  </header>
</template>
