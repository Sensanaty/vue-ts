<template>
  <RouterView />
</template>

<script setup lang="ts">
  import { useHead } from "@vueuse/head";

  useHead({
    title: "L U K A",
    meta: [{ name: "description", content: "Luka Salević is a Fullstack Engineer with expertise in JavaScript, Ruby, Go, Elixir and Crystal" }]
  });
</script>
