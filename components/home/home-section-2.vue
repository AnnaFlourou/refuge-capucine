<template>
  <div class="homepage-section-2" >
    <Phrase-banner :phrase="phrase"/>
  </div>
</template>

<script>
import PhraseBanner from "@/components/common/phrase-banner";
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo,
    PhraseBanner
  },
  data(){
    return {
      phrase: {
        text: " Regarde ton chien dans les yeux et tu ne pourras affirmer qu’il n’a pas d’âme.",
        author: "Victor Hugo",
        urlImg: '/img/banner/banner-5.jpg'
      }
    }
  }
};
</script>

