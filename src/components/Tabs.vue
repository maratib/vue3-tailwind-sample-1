<script setup lang="ts">
import ClientForm from "./ClientForm.vue";
</script>
<template>
  <!-- Form Tabs -->
  <div class="flex space-x-1">
    <span class="bg-white p-4 text-xl rounded-tr-xl rounded-tl-xl"
      >Info. Cliente</span
    >
    <span
      class="bg-[#52AE82] bg-opacity-[62%] p-4 rounded-tr-xl rounded-tl-xl text-white text-xl text-opacity-[62%]"
    >
      Info. Complementaria
    </span>
    <span
      class="bg-[#52AE82] bg-opacity-[62%] p-4 rounded-tr-xl rounded-tl-xl text-white text-xl text-opacity-[62%]"
    >
      Info. Historica
    </span>
  </div>
  <!-- Form Starts -->
  <ClientForm />

  <!-- Form Ends -->
</template>
