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
        <a href="#" class="nav_links">
          <LayoutIcon />
        </a>
      </li>
      <li>
        <a href="#" class="nav_links"> <CalenderIcon /> </a>
      </li>
      <li>
        <a href="#" class="nav_links">
          <OperatorIcon />
        </a>
      </li>
      <li>
        <a href="#" class="nav_links">
          <PieIcon />
        </a>
      </li>
      <li>
        <a href="#" class="nav_links"> <GraphIcon /> </a>
      </li>
      <li>
        <a href="#" class="nav_links">
          <UserIcon />
        </a>
      </li>
    </ul>
  </nav>
</template>
