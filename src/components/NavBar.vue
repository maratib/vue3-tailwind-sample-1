<script setup lang="ts">
import LayoutIcon from "./icons/LayoutIcon.vue";
import CalenderIcon from "./icons/CalenderIcon.vue";
import OperatorIcon from "./icons/OperatorIcon.vue";
import PieIcon from "./icons/PieIcon.vue";
import GraphIcon from "./icons/GraphIcon.vue";
import UserIcon from "./icons/UserIcon.vue";
</script>
<template>
  <nav class="">
    <ul class="flex gap-5">
      <li>
        <a href="#"> <LayoutIcon /> </a>
      </li>
      <li>
        <a href="#"> <CalenderIcon /> </a>
      </li>
      <li>
        <a href="#">
          <OperatorIcon />
        </a>
      </li>
      <li>
        <a href="#">
          <PieIcon />
        </a>
      </li>
      <li>
        <a href="#"> <GraphIcon /> </a>
      </li>
      <li>
        <a href="#">
          <UserIcon />
        </a>
      </li>
    </ul>
  </nav>
</template>
