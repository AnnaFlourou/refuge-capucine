<template>
  <div class="homepage-section-1">
    <video-bg :sources="['/video/Dog-in-Farm.mp4']" img="/video/Dog-in-Farm.jpg">
      <!-- If you want to add content here, a slot is waiting! -->
    </video-bg>
  </div>
</template>

<script>
import VideoBg from "vue-videobg";
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo,
    VideoBg
  }
};
</script>

