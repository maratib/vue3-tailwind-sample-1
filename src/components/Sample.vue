<script setup lang="ts">
// Imports
import { ref } from "vue";

// Props
defineProps<{ msg?: string }>();

// Reactive
const count = ref(0);

// Variables
const msg = "Sample Message";

// Functions
function log() {
  console.log(msg);
}
</script>

<template>
  <div @click="log">{{ msg }}</div>
  <button class="bg-red-500 p-4 m-4 text-white" @click="count++">
    {{ count }}
  </button>
</template>
