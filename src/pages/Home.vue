<template>
  <div class="w-full relative">
    <info-bar />
    <navbar />
    <banner />
  </div>
</template>

<script>
import InfoBar from "../components/InfoBar.vue";
import Navbar from "../components/Navbar.vue";
import Banner from "../components/Banner.vue";

export default {
  name: "Home",
  components: {
    InfoBar,
    Navbar,
    Banner
  }
}
</script>

<style scoped>

</style>