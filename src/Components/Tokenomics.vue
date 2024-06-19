<script lang="ts">
import Button from "../Common/Button.vue";

export default {
  components: {
    Button,
  },
};
</script>
<template id="about">
  <section class="w-full">
    <div
      class="w-full relative flex flex-col lg:flex-row items-center pt-6 lg:pt-[104px] container"
    >
      <div class="w-full lg:w-1/2">
        <h1
          data-aos="fade-up"
          class="text-[32px] lg:text-[64px] font-bold lg:leading-[96px] text-left text_gradient"
        >
          Tokenomics
        </h1>
        <p
          data-aos="fade-up"
          class="text-2xl font-bold leading-9 text-left text-[#E8F4F1] mt-[36px]"
        >
          Token Supply: 375,906,235,908,32
        </p>
        <ul class="flex flex-col gap-y-6 mt-[36px]">
          <li class="flex items-center gap-x-5">
            <div class="w-[52px] h-[24px] green_gradient rounded-[24px]"></div>
            <span
              data-aos="fade-up"
              class="text-base font-semibold leading-6 text-[#E8F4F1] text-left"
            >
              34% team (lock for 6 months{</span
            >
          </li>
          <li data-aos="fade-up" class="flex items-center gap-x-5">
            <div class="w-[52px] h-[24px] yellow_gradient rounded-[24px]"></div>
            <span
              class="text-base font-semibold leading-6 text-[#E8F4F1] text-left"
            >
              10% marketing</span
            >
          </li>
          <li data-aos="fade-up" class="flex items-center gap-x-5">
            <div class="w-[52px] h-[24px] yellow_gradient rounded-[24px]"></div>
            <span
              class="text-base font-semibold leading-6 text-[#E8F4F1] text-left"
            >
              30% Lp+ staking Rewards</span
            >
          </li>
          <li data-aos="fade-up" class="flex items-center gap-x-5">
            <div class="w-[52px] h-[24px] green_gradient rounded-[24px]"></div>
            <span
              class="text-base font-semibold leading-6 text-[#E8F4F1] text-left"
            >
              30% Airdrop</span
            >
          </li>
        </ul>
      </div>
      <div class="w-full lg:w-1/2">
        <img data-aos="fade-up" src="../Assets/chart.png" alt="" />
      </div>
    </div>
    <div
      class="hidden lg:inline-block green_blur w-[1134px] h-[1134px] absolute left-[-700px]"
    />
  </section>
</template>

<style scoped></style>
