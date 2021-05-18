<template>
  <div class="w-full flex justify-center items-center bg-white">
    <div class="container p-8">
      <div class="w-full bg-background-primary rounded-md px-24 pt-16 grid grid-cols-2">
        <div class="w-full flex flex-col justify-center h-full">
          <h2 class="text-4xl font-bold text-black leading-normal mb-2">Secure your money<br>with Escrow.</h2>
          <p class="leading-normal mb-4">
            Spense uses Escrow to secure all payments. We believe Escrow offers the highest level of security for your payments, so you never need to worry about scams.
          </p>
          <a class="font-bold cursor-pointer underline">Learn more about Escrow -></a>
        </div>
        <div class="w-full flex justify-end items-center">
          <base-image src="phone.png" class="w-full md:max-w-80" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BaseImage from "./basics/BaseImage.vue";

export default {
  name: "EscrowSection",
  components: {
    BaseImage
  }
}
</script>

<style scoped>

</style>