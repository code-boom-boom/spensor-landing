<template>
  <div class="w-full bg-white flex justify-center">
    <div class="container grid grid-cols-8 gap-8 py-16">
      <base-image v-for="(image, index) in images" :key="index" :src="image" class="w-full px-4 flex items-center justify-center" />
    </div>
  </div>
</template>

<script>
import BaseImage from "./basics/BaseImage.vue";

export default {
  name: "ClientBar",
  components: {BaseImage},
  data() {
    return {
      images: [
          'facebook.png',
          'dribbble.png',
          'youtube.png',
          'pinterest.png',
          'twitter.png',
          'reddit.png',
          'google.png',
          'slack.png',
      ]
    };
  }
}
</script>

<style scoped>

</style>