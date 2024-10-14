<!-- @format -->
<script setup lang="ts">
useHead({
  title: "Awesome Nuxtjs",
  script: [{ src: "/assets/js/main.js" }],
  meta: [{ name: "A test name", content: "We are dealing with NuxtJS" }],
});
definePageMeta({
  //layout: false,
});
</script>

<template>
  <div class="">
    <h2>The Home</h2>
  </div>
</template>
