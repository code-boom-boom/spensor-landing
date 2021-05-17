<template>
  <div>
    <img :src="getImgUrl(src)" :alt="src">
  </div>
</template>

<script>
export default {
  name: "BaseImage",
  props: {
    src: {
      required: true,
      type: String,
    }
  },
  methods: {
    getImgUrl(imgName) {
      return require('../../assets/'+imgName)
    }
  }
}
</script>

<style scoped>

</style>