<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavigationBar from './components/Navigation/NavigationBar.vue'
</script>

<template>
  <NavigationBar />
  <RouterView class="w-full h-full fixed top-12 overflow-y-auto min-w-fit" style="height: calc(100% - 3rem)"/>
</template>
