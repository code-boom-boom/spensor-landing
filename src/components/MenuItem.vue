<template>
  <p><a class="cursor-pointer">{{ name }}</a></p>
</template>

<script>
export default {
  name: "MenuItem",
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