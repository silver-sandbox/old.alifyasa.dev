<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
defineProps<{
  button_path: string,
  button_label: string
}>()
</script>

<template>
  <RouterLink 
    class="h-full w-full flex items-center justify-center transition-colors duration-200 hover:bg-zinc-600 font-montserrat font-medium text-zinc-100" 
    :class="{'bg-zinc-600': $route.path === `${button_path}`}"
    :to="`${button_path}`">
  {{ button_label }}
  </RouterLink>
</template>
