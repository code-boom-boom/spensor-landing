<template>
  <div class="w-full relative">
    <info-bar />
    <navbar />
    <banner />
    <client-bar />
    <escrow-section />
    <editor-section />
    <footer-bar />
  </div>
</template>

<script>
import InfoBar from "../components/InfoBar.vue";
import Navbar from "../components/Navbar.vue";
import Banner from "../components/Banner.vue";
import ClientBar from "../components/ClientBar.vue";
import EscrowSection from "../components/EscrowSection.vue";
import EditorSection from "../components/EditorSection.vue";
import FooterBar from "../components/FooterBar.vue";

export default {
  name: "Home",
  components: {
    InfoBar,
    Navbar,
    Banner,
    ClientBar,
    EscrowSection,
    EditorSection,
    FooterBar
  }
}
</script>

<style scoped>

</style>