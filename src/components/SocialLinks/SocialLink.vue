<script setup lang="ts">
defineProps<{
  link_: string,
  img_: string,
  alt_: string
}>()
</script>

<template>
  <a 
    class="h-full inline-block align-middle rounded-sm"
    :href="link_"
    target="_blank"
    :aria-label="`${alt_} Link`"
  >
    <img 
      class="object-contain object-center h-full w-full" 
      :src="img_" 
      :alt="`${alt_} Logo`"
    />
  </a>
</template>
