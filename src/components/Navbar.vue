<template>
  <div class="w-full flex justify-center items-center py-8">
    <div class="container">
      <div class="flex justify-between items-center">
        <h2 class="text-2xl font-bold">spense.</h2>
        <div class="grid grid-cols-3 gap-4">
          <menu-item name="Business" />
          <menu-item name="Pricing" />
          <menu-item name="Features" />
        </div>
        <div class="flex justify-end items-center">
          <menu-item name="Login" class="mr-4" />
          <base-button name="Get Started" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MenuItem from "./MenuItem.vue";
import BaseButton from "./basics/BaseButton.vue";

export default {
  name: "Header",
  components: {
    MenuItem,
    BaseButton
  }
}
</script>

<style scoped>

</style>