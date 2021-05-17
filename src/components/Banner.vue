<template>
  <div class="w-full flex justify-center items-center">
    <div class="container">
      <div class="flex flex-col-reverse md:flex-row my-8">
        <div class="w-1/2 w-full flex flex-col justify-center p-8">
          <h1 class="text-5xl font-bold text-black leading-relaxed mb-4">Share your unfiltered<br>thoughts. Get paid.</h1>
          <p class="leading-normal">Spense is an open platform for individuals to share their unfiltered thoughts. <br> Discuss the topics you love, and get paid for doing <em>just</em> that.</p>
          <ul class="checkmark mt-4">
            <li>Receive 99% off the earnings.</li>
            <li>Get paid via Debit Card, ACH, or PayPal.</li>
            <li>Withdraw your earnings anytime.</li>
          </ul>
          <div class="mt-4 flex items-center">
            <input type="text" placeholder="john@example.com" class="border border-gray-400 rounded h-full p-4 mr-4">
            <base-button name="Get Started" />
          </div>
        </div>
        <div class="w-1/2 w-full flex justify-end items-center p-8">
          <base-image src="Hero-Image.png" class="w-full md:max-w-80" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BaseImage from "./basics/BaseImage.vue";
import BaseButton from "./basics/BaseButton.vue";

export default {
  name: "Banner",
  components: {
    BaseImage,
    BaseButton
  }
}
</script>

<style lang="sass" scoped>
ul.checkmark li
  font-size: 16px // modify to test
  margin-bottom: 1em
  list-style-type: none
  padding: .25em 0 0 2.5em
  position: relative
  &:before
    content: " "
    display: block
    border: solid .8em black
    border-radius: .8em
    height: 0
    width: 0
    position: absolute
    left: .5em
    top: 40%
    margin-top: -.5em
  &:after
    content: " "
    display: block
    width: .3em
    height: .6em
    border: solid #fff
    border-width: 0 .2em .2em 0
    position: absolute
    left: 1.2em
    top: 40%
    margin-top: -.1em
    -webkit-transform: rotate(45deg)
    -moz-transform: rotate(45deg)
    -o-transform: rotate(45deg)
    transform: rotate(45deg)
</style>