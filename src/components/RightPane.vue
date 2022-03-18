<script setup lang="ts">
import DotsIcon from "./icons/DotsIcon.vue";
</script>
<template>
  <!-- Right Side Starts -->
  <div class="mt-64 w-64 h-80 flex space-x-4 p-4">
    <!-- Date & time starts -->
    <div class="whitespace-nowrap text-right h-full">
      <span>
        <p>26-12-2019</p>
        <p>12:20</p>
      </span>
      <span class="">
        <p class="mt-16">26-12-2019</p>
        <p>12:13</p>
      </span>
      <span class="">
        <p class="mt-16">26-12-2019</p>
        <p>11:54</p>
      </span>
    </div>
    <!-- Date & time ends -->
    <!-- Green Points Starts-->
    <div class="flex flex-col items-center">
      <span class="bg-[#52AE82] h-8 w-8 rounded-full"></span>
      <hr class="w-1 h-20 bg-[#52AE82]" />
      <span class="bg-[#52AE82] h-8 w-8 rounded-full"></span>
      <hr class="w-1 h-20 bg-[#52AE82]" />
      <span class="bg-[#52AE82] h-8 w-8 rounded-full"></span>
    </div>
    <!-- Green Points Ends-->
    <div class="whitespace-nowrap">
      <p>En Seguimiento</p>
      <div
        class="shadow-inner shadow-[rgba(0,0,0,0.25)] bg-[#B3B0B0] p-2 bg-white mt-12 flex flex-col justify-center items-center rounded-sm overflow-hidden"
      >
        <span class="flex justify-between items-center space-x-1">
          <p class="text-sm">Liamar proximia</p>
          <DotsIcon />
        </span>
        <p class="-mb-4 -ml-14 text-sm">aiam aiospsi</p>
      </div>
      <p class="mt-1">En Seguimiento</p>
      <div
        class="shadow-inner shadow-[rgba(0,0,0,0.25)] bg-[#B3B0B0] p-2 bg-white mt-11 flex flex-col justify-center items-center rounded-sm overflow-hidden"
      >
        <span class="flex justify-between items-center space-x-1">
          <p class="text-sm -ml-2">Liamar proximia</p>
          <DotsIcon />
        </span>
        <p class="-mb-4 -ml-16 text-sm">aiam aiospsi</p>
      </div>
      <p class="mt-1">Inicio</p>
    </div>
  </div>
  <!-- Right Side Ends -->
</template>
