<script setup lang="ts">
import SocialLink from "./SocialLink.vue"

import GitHub_Logo from "@/assets/social_logo/github.png"
// import Kaggle_Logo from "@/assets/social_logo/kaggle.png"
import LinkedIn_Logo from "@/assets/social_logo/linkedin.png"
</script>

<template>
  <div aria-label="Social Media Profiles" class="absolute bottom-0 w-full h-1/6">
  <div 
    class="w-full bg-zinc-600 font-montserrat text-zinc-100 font-medium py-1 h-1/3 xl:text-2xl text-lg flex justify-center items-center"
    aria-label="Section Title"
    >FOLLOW ME</div>
  <div class="w-full py-2 xl:py-4 bg-zinc-100 flex justify-evenly h-2/3">
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
