<!-- @format -->

<template>
  <div>
    <AppHeader />
    <div
      class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-6 gap-3 md:gap-8 py-10 max-sm:max-w-sm max-sm:mx-auto gap-y-8 min-h-screen"
    >
      <slot />
    </div>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "@/components/navigation/AppHeader.vue";
import AppFooter from "@/components/navigation/AppFooter.vue";

export default {
  name: "DefaultLayout",

  components: {
    AppHeader,
    AppFooter,
  },
};
</script>
