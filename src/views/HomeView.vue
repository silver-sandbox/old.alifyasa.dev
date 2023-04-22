<script setup lang="ts">
import SocialLinks from '../components/SocialLinks/SocialLinks.vue'
</script>

<template>
  <main aria-label="Page Content">
    <div
        class="font-bodoni-moda w-full text-zinc-100 px-16 flex flex-col justify-center overflow-x-hidden overflow-y-auto absolute top-0"
        style="height: calc(100% - 8rem)"
      >
      <div 
        class="sm:text-8xl xl:text-9xl/tight text-right my-8 w-full"
        aria-label="My Name"
      >
      Muhammad <span class="underline">Alif</span><br/>Putra <span class="underline">Yasa</span>
      </div>
      <div
        class="sm:text-2xl xl:text-3xl/tight text-left w-full my-4 italic"
        aria-label="Short description about myself"
      >
      <a href="https://stei.itb.ac.id/en/undergraduate-programs/bachelor-informatics/" target="_blank">
        <span class="underline hover:bg-zinc-600">Informatics Engineering</span>
      </a> student at
      <a href="https://www.itb.ac.id/en/" target="_blank">
        <span class="underline hover:bg-zinc-600">Bandung Institute of Technology</span>
      </a>. Interested in Automation and Machine Learning.
      </div>
    </div>
    <SocialLinks />
  </main>
</template>
