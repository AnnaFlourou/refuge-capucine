<template>
  <div
    class="phrase-banner container mx-auto"
    :style="'background-image: url(' + phrase.urlImg + ')' "
  >
    <div class="phrase">
      <div class="text">{{phrase.text}}</div>
      <div class="author">
        {{phrase.author}}
        <span>.</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  props: ["phrase"]
};
</script>

