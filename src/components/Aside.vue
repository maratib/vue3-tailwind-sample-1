<script setup lang="ts">
import SearchBox from "./SearchBox.vue";
import Tags from "./Tags.vue";
import Card from "./Card.vue";
const myMsgs = [
  "Jorge S",
  "111111131",
  "jsantibanez@openpartner.cl",
  "EN SEGUIMIENTO",
];
</script>
<template>
  <aside
    class="w-74 bg-gray-100 min-h-screen p-5 shadow-[4px_0px_4px_rgba(0,0,0,0.1)]"
  >
    <!-- Search bar start -->
    <div class="flex justify-between items-center w-52">
      <SearchBox />
    </div>
    <!-- Search bar end-->
    <!-- Co-Web Starts-->
    <div class="flex flex-col w-32 mt-11">
      <Tags />
    </div>
    <!-- Co-Web End -->
    <!-- Cards -->
    <div class="mt-16 space-y-5">
      <!-- Card-1 -->
      <Card
        media="WEB"
        tickets="80801"
        dated="21-11-2019, 12:10:11"
        num="9978078212"
      />
      <!-- Card-2 -->
      <Card
        media="WEB"
        tickets="80808"
        dated="26-12-2019, 12:22:09"
        num="9978078011"
        :msgs="myMsgs"
      />
      <!-- Card-3 -->
      <Card
        media="WEB"
        tickets="90901"
        dated="11-11-2019, 12:45:35"
        num="55580744344"
      />

      <!-- Card-4 -->
      <Card
        media="WEB"
        tickets="80777"
        dated="10-11-2019, 12:02:15"
        num="9978071212"
      />
    </div>
  </aside>
</template>
