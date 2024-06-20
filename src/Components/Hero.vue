<script lang="ts">
import Button from "../Common/Button.vue";

export default {
  components: {
    Button,
  },
};
</script>
<template>
  <section class="w-full">
    <div
      class="w-full pt-0 lg:pt-[138px] container relative flex lg:flex-row flex-col-reverse"
    >
      <div class="w-full lg:w-1/2">
        <h1
          data-aos="fade-up"
          class="text-[36px] font-bold lg:leading-[92px] text-left text-[#E8F4F1]"
        >
          <span class="text_gradient">PepeChat:</span> Expert Advice Real-Time
          Chat
        </h1>
        <p
          data-aos="fade-up"
          class="text-base lg:w-auto w-full font-semibold my-5 lg:py-[36px] text-[#C3C3C3] leading-6 text-left"
        >
          Our chat website connects you with fellow Pepe enthusiasts and
          experts. Ask questions and share knowledge about rare Pepes, meme
          history, and responsible collecting. Test your Pepe IQ with quizzes
          and fun games, or even unleash your creativity by designing your own
          Pepe art. We prioritize a safe and respectful chat environment with
          clear guidelines and moderation.
        </p>
        <div data-aos="fade-up" class="flex w-full gap-x-6">
          <Button label="Buy Now!" variant="primary" class="lg:w-auto w-full" />
          <Button
            label="Chat Now!"
            variant="outline"
            class="lg:w-auto w-full"
          />
        </div>
      </div>
      <div class="w-full lg:w-1/2">
        <img
          class="w-[264px] h-[306px] lg:w-[464px] lg:h-[406px] object-cover"
          src="../Assets/hero.png"
          alt="PepeChat"
          data-aos="fade-up"
        />
        <img
          data-aos="fade-up"
          src="../Assets/email.png"
          alt=""
          class="absolute h-[600px] lg:!w-[791px] lg:h-[791px] rotate-z-[64.48deg] -top-20 right-0 -z-10"
        />
      </div>
    </div>
    <div data-aos="fade-up" class="w-full container px-4 lg:px-8 mt-[41px]">
      <div class="border_gradient w-full rounded-[8px]">
        <div
          class="w-full grid grid-cols-1 lg:grid-cols-4 shadow-[0px_0px_8px_0px_#56FF7B59] rounded-[8px]"
        >
          <div class="border_right_gradient py-3 lg:py-10">
            <h3
              class="text-4xl font-bold leading-[54px] text-center text_gradient"
            >
              8
            </h3>
            <p
              class="text-xl font-bold leading-[30px] text-center text_gradient"
            >
              Taxers
            </p>
          </div>
          <div class="border_right_gradient py-3 lg:py-10">
            <h3
              class="text-4xl font-bold leading-[54px] text-center text_gradient"
            >
              7523
            </h3>
            <p
              class="text-xl font-bold leading-[30px] text-center text_gradient"
            >
              Holders
            </p>
          </div>
          <div class="border_right_gradient py-3 lg:py-10">
            <h3
              class="text-4xl font-bold leading-[54px] text-center text_gradient"
            >
              854
            </h3>
            <p
              class="text-xl font-bold leading-[30px] text-center text_gradient"
            >
              Most Pepe
            </p>
          </div>
          <div class="py-10">
            <h3
              class="text-4xl font-bold leading-[54px] text-center text_gradient"
            >
              854
            </h3>
            <p
              class="text-xl font-bold leading-[30px] text-center text_gradient"
            >
              Most Pepe
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.border_right_gradient {
  position: relative;
}
.border_right_gradient::before {
  content: "";
  position: absolute;
  right: 0px;
  top: 0px;
  width: 2px;
  height: 100%;
  background: linear-gradient(
    90deg,
    #0a2d0e -0.87%,
    #3cff71 51.51%,
    #061703 100%
  );
  border-radius: 250% !important;
}
</style>
