<template>
  <div class="home">
     <video src="/video/Dog-in-Farm.mp4">
      <!-- <p>Your browser does not support the video tag.</p> -->
      <video id="example_video_1" class="video-js vjs-default-skin" controls     preload="none" width="100%" height="300" setup="{}">
    <source src="/video/Dog-in-Farm.mp4" type="video/mp4">
</video>
    </video>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

