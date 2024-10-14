<!-- @format -->

<script setup>
useHead({
  title: "About page",
});

definePageMeta({
  colorMode: "sepia",
  layout: "admin",
});

const { data } = await useFetch("/api/userdetails");
console.log("My data was", data.value.mssg);
</script>

<template>
  <div class="">
    <h2>About Page</h2>
    <p>{{ data.mssg }}</p>
  </div>
</template>
