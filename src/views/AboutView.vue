<template>
  <div class="px-16 text-zinc-100 font-montserrat">
    <div class="flex justify-start gap-8 my-16">
      <h1 class="text-5xl font-bold">
        ABOUT ME
      </h1>
      <button @click="openPDF" class="bg-zinc-700 hover:bg-zinc-600 font-bold px-4 rounded-sm">
        RESUME
      </button>
    </div>
    <div class="text-2xl/relaxed whitespace-normal overflow-y-auto my-16 space-y-4" aria-label="Introduction">
      <p>
        I am Alif and I am currently a 6th semester student studying
        <a href="https://stei.itb.ac.id/en/undergraduate-programs/bachelor-informatics/" target="_blank">
          <span class="underline hover:bg-zinc-600">Informatics Engineering</span>
        </a> at 
        <a href="https://www.itb.ac.id/en/" target="_blank">
          <span class="underline hover:bg-zinc-600">Bandung Institute of Technology</span>
        </a>. My primary interests include DevOps and Cloud Computing, with a focus on task automation projects such as CI/CD and Data Engineering in my personal projects. In addition, I am currently enhancing my skills in Mathematics and Statistics to broaden my scope of knowledge and delve into the fields of Data Analytics and Machine Learning.
      </p>
      <p>
        Feel free to
        <a href="https://www.linkedin.com/in/muhammad-alif-putra-yasa-a91793219" target="_blank">
          <span class="underline hover:bg-zinc-600">connect with me on LinkedIn</span>
        </a> or
        <a href="mailto:contact@alifyasa.dev" target="_blank">
          <span class="underline hover:bg-zinc-600">send me an email</span>
        </a> if you'd like to chat more or collaborate on a project!
      </p>
    </div>
  </div>
</template>

<script lang="ts">
import resumePDF from '@/assets/Resume.pdf';
export default {
  methods: {
    openPDF(): void {
      window.open(resumePDF, '_blank');
    }
  }
};
</script>
