<script setup lang="ts">
import Header from "@/components/Header.vue";
import Aside from "@/components/Aside.vue";
import TogglerButton from "@/components/TogglerButton.vue";
import Points from "./components/Points.vue";
import Tabs from "./components/Tabs.vue";
import RightPane from "./components/RightPane.vue";
</script>

<template>
  <div class="root min-h-screen">
    <Header />
    <div class="flex">
      <Aside />
      <!-- Slot -->
      <div class="bg-gray-400 w-7/12">
        <div class="flex items-center mt-12">
          <!-- Navbar Toggler -->
          <TogglerButton />
          <Points />
        </div>
        <div class="mr-6 ml-14 mt-28">
          <Tabs />
        </div>
      </div>

      <RightPane />
    </div>
  </div>
</template>
