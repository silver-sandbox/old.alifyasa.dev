<script setup lang="ts">
defineProps<{
  title_: string,
  link_: string
}>()
</script>

<template>
  <div class="bg-zinc-100 rounded-sm">
    <h2 class="p-8 text-4xl bg-zinc-700">
      <a :href="link_" target="_blank" class="hover:underline">
        {{ title_ }} <span class="material-symbols-outlined" aria-label="Open in New Icon"> open_in_new </span>
      </a>
    </h2>
    <div class="text-xl p-8 text-zinc-700 space-y-4">
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.material-symbols-outlined {
  font-variation-settings:
  'FILL' 0,
  'wght' 400,
  'GRAD' 0,
  'opsz' 48
}
</style>
