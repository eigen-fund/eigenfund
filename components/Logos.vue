<script setup>
const props = defineProps({
  title: String,
  icons: Array
});
</script>

<template>
  <div class="mb-20">
    <h2 class="text-center text-zinc-600" v-if="title">{{ title }}</h2>
    <div class="flex flex-wrap items-center justify-center mt-10 gap-x-12 gap-y-8 sm:gap-x-24 sm:gap-y-12">
        <NuxtImg
          v-for="icon in icons"
          :key="icon.src"
          :src="icon.src"
          :alt="icon.alt"
          class="w-10 h-auto rounded-sm"
        />

    </div>
  </div>
</template>
