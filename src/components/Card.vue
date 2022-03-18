<script setup lang="ts">
import WebIcon from "./icons/WebIcon.vue";
import HandIcon from "./icons/HandIcon.vue";
import DateIcon from "./icons/DateIcon.vue";
defineProps<{
  media?: string;
  tickets?: string;
  dated?: string;
  num?: string;
  msgs?: string[];
}>();
</script>

<template>
  <div class="bg-white border-[#D0D4D4] border-2 w-72">
    <ul class="p-3 space-y-4">
      <li class="flex items-center gap-3">
        <WebIcon />
        <p>{{ media }}</p>
      </li>
      <li class="flex items-center gap-3">
        <HandIcon />
        <p class="font-semibold">{{ tickets }}</p>
      </li>
      <li class="flex items-center gap-3">
        <DateIcon />
        <p>{{ dated }}</p>
      </li>
    </ul>
    <div v-if="msgs" class="bg-[#EAEAEA]">
      <ul class="p-3">
        <li v-for="msg in msgs" :key="msg">{{ msg }}</li>
      </ul>
    </div>
    <div class="m-2" v-if="num">
      <div
        class="flex items-center justify-between bg-[#D0D4D4] p-2 rounded-md"
      >
        <p class="font-light">{{ num }}</p>
        <span
          class="rounded-full border-[#5BCD97] border-2 bg-white w-7 text-center"
        >
          1
        </span>
      </div>
    </div>
  </div>
</template>
