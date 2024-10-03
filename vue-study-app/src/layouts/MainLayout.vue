<script setup lang="ts">
  import { RouterView } from "vue-router";
</script>

<template>
  <div>Tour of Heroes</div>
  <button>Dashboard</button>
  <button>Heroes</button>

  <!-- Dit is waar de children getoond worden -->
  <RouterView />
</template>