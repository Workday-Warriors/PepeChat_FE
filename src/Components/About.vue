<script lang="ts">
import Button from "../Common/Button.vue";
import Play from "../Icons/play.vue"

export default {
  components: {
    Button,
    Play
  },
};
</script>
<template id="about" >
  <section class="w-full">
    <div class="w-full container flex items-center justify-between pt-[124px]">
    <div class="w-1/2" >
        <h1 class="text-[64px] text-[#E8F4F1] font-bold leading-[96px] text-left">
        About <br />
        <span class="text_gradient">PepeChat</span>
      </h1>
      <p class="text-base my-[36px] font-semibold text-[#C3C3C3] leading-6 text-left" >
        Our chat website connects you with fellow Pepe enthusiasts and experts.
        Ask questions and share knowledge about rare Pepes, meme history, and
        responsible collecting. Test your Pepe IQ with quizzes and fun games, or
        even unleash your creativity by designing your own Pepe art.
      </p>
      <div class="flex items-center  gap-x-6" >
        <Button label="Contact Us" variant="primary" />
        <Button label="Learn More" variant="outline" /> 
      </div>
    </div>
    <div class="w-1/2 h-full flex justify-end" >
            <div class="w-[597px] h-[370px] relative" >
                <img src="../Assets/about-image.png" alt="">
                <Play class="absolute top-[50%] left-[50%] translate-x-[-50%] translate-y-[-50%] cursor-pointer" />
            </div>
    </div>
    </div>
  </section>
</template>

<style scoped></style>
