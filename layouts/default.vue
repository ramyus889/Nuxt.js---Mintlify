<script setup lang="ts">
useHead({
  title: "Mintlify747",
  meta: [
    { name: "viewport", content: "width=device-width, initial-scale=1" },
    { name: "description", content: "Nuxt 3 Frontend Development" },
  ],
  link: [{ rel: "icon", type: "image/x-icon", href: "/img/Code/frontend.jpg" }],
});
</script>
<template>
  <div class="">
    <UseHeader />
  </div>
  <div class="">
    <slot />
  </div>
</template>
