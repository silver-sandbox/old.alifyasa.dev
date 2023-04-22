<script setup lang="ts">
import SocialLink from "./SocialLink.vue"

import GitHub_Logo from "@/assets/social_logo/github.png"
// import Kaggle_Logo from "@/assets/social_logo/kaggle.png"
import LinkedIn_Logo from "@/assets/social_logo/linkedin.png"
</script>

<template>
  <div aria-label="Social Media Profiles" class="absolute bottom-0 w-full">
  <div 
    class="w-full bg-zinc-600 text-center font-montserrat text-2xl text-zinc-100 font-medium py-2"
    aria-label="Section Title"
    >FOLLOW ME</div>
  <div class="w-full px-4 bg-zinc-100 flex justify-evenly">
    <SocialLink 
      link_="https://github.com/malifpy" 
      :img_=GitHub_Logo
      alt_="GitHub"
    />
    <!-- <SocialLink  -->
    <!--   link_="https://kaggle.com/malifpy"  -->
    <!--   :img_="Kaggle_Logo" -->
    <!--   alt_="Kaggle" -->
    <!-- /> -->
    <SocialLink 
      link_="https://www.linkedin.com/in/muhammad-alif-putra-yasa-a91793219" 
      :img_="LinkedIn_Logo"
      alt_="LinkedIn"
    />
  </div>
  </div>
</template>
