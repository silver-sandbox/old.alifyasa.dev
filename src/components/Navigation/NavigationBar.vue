<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavigationButton from './NavigationButton.vue'
</script>

<template>
  <nav
    class="w-full bg-zinc-700 h-12 flex justify-between fixed top-0"
    aria-label="Navigation Bar"
  >
    <NavigationButton button_label="HOME" button_path='/' />
    <NavigationButton button_label="PROJECTS" button_path='/projects' />
    <NavigationButton button_label="ABOUT" button_path='/about' />
  </nav>
</template>
