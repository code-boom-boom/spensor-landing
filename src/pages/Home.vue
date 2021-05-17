<template>
  <div class="w-full relative">
    <info-bar />
    <navbar />
    <banner />
    <client-bar />
  </div>
</template>

<script>
import InfoBar from "../components/InfoBar.vue";
import Navbar from "../components/Navbar.vue";
import Banner from "../components/Banner.vue";
import ClientBar from "../components/ClientBar.vue";

export default {
  name: "Home",
  components: {
    InfoBar,
    Navbar,
    Banner,
    ClientBar
  }
}
</script>

<style scoped>

</style>