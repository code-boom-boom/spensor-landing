<template>
  <div class="rounded bg-black py-3 px-4">
    <p class="text-white">{{ name }}</p>
  </div>
</template>

<script>
export default {
  name: "BaseButton",
  props: {
    name: {
      required: true,
      type: String
    }
  }
}
</script>

<style scoped>

</style>