<template>
  <div class="w-full flex justify-center items-center bg-white">
    <div class="container p-8">
      <div class="w-full pt-16 grid grid-cols-7">
        <div class="w-full col-span-4 flex justify-end items-center">
          <base-image src="editor.png" class="w-full" />
        </div>
        <div class="w-full col-span-3 flex flex-col justify-center h-full">
          <h2 class="text-4xl font-bold text-black leading-normal mb-2">A text editor like no other.</h2>
          <p class="leading-normal mb-4">
            Our text editor pulls you into focus mode with it's simplistic design and usability so you can put out your best writings.
          </p>
          <a class="font-bold cursor-pointer underline">Text Editor Live Demo -></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BaseImage from "./basics/BaseImage.vue";

export default {
  name: "EditorSection",
  components: {
    BaseImage
  }
}
</script>

<style scoped>

</style>