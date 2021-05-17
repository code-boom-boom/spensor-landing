<template>
  <div class="w-full relative">
    <info-bar />
    <navbar />
  </div>
</template>

<script>
import InfoBar from "../components/InfoBar.vue";
import Navbar from "../components/Navbar.vue";

export default {
  name: "Home",
  components: {
    InfoBar,
    Navbar
  }
}
</script>

<style scoped>

</style>