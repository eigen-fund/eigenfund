<script setup>
useHead({
  htmlAttrs: { lang: "en-US" },
  title: "Eigen Fund",
  meta: [
    {
      name: "description",
      content:
        "Eigen Fund Website uses Nuxt 3 and Tailwind CSS.",
    },
  ],
  bodyAttrs: {
    class: 'font-display'
  }
});
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
