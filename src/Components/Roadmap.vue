<script lang="ts">
import Button from "../Common/Button.vue";
import Check from "../Icons/Check.vue";
import Close from "../Icons/Close.vue";

export default {
  components: {
    Button,
    Check,
    Close,
  },
};
</script>
<template>
  <section id="roadmap" class="w-full relative">
    <div
      class="flex flex-col lg:flex-row relative container px-4 lg:px-8 justify-between gap-x-[77px]"
    >
      <div
        class="w-full lg:w-[47.5%] flex gap-y-6 lg:gap-y-[410px] flex-col items-end justify-end"
      >
        <div class="lg:w-auto w-full">
          <div
            data-aos="fade-up"
            class="py-4 lg:py-[38px] shadow-[0px_0px_6px_0px_#3CFF71] w-full lg:w-[475.42px] inline-block px-5 lg:px-[36px] rounded-[22px] border-[0px,0.5px,0.5px,0.5px] border-solid bg-[#081506] border-[#E8F4F1]"
          >
            <h1
              class="text-[28px] lg:text-5xl text-[#3CFF71] font-bold lg:leading-[72px] text-left"
            >
              Phase 1
            </h1>
            <ul class="flex flex-col mt-[26px] gap-y-[18px]">
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                Contract Creation
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                Website Designing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                Token Launch
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                Budling Community
              </li>
            </ul>
          </div>
        </div>

        <div class="lg:w-auto hidden lg:block w-full">
          <div
            data-aos="fade-up"
            class="py-4 lg:py-[38px] mt-6 lg:mt-0 shadow-[0px_0px_6px_0px_#3CFF71] w-full lg:w-[475.42px] inline-block px-5 lg:px-[36px] rounded-[22px] border-[0px,0.5px,0.5px,0.5px] border-solid bg-[#081506] border-[#E8F4F1]"
          >
            <h1
              class="text-[28px] lg:text-5xl font-bold lg:leading-[72px] text-left text-[#3CFF71]"
            >
              Phase 3
            </h1>
            <ul class="flex flex-col mt-[26px] gap-y-[18px]">
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                Dextools Listing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                Stake Live
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                CoinMarketCap Listing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                Partnerships
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div class="hidden w-[5%] lg:flex justify-center">
        <div class="w-[3px] h-[70%] roadmap_line relative">
          <div
            class="w-[84px] absolute -top-4 right-1/2 translate-x-1/2 h-[84px] rounded-full green_gradient text-[32px] font-bold leading-[38.73px] flex justify-center items-center"
          >
            1
          </div>
          <div
            class="w-[84px] absolute top-1/2 -translate-y-[80%] right-1/2 border border-solid border-[#E8F4F1] translate-x-1/2 h-[84px] text-[#3CFF71] rounded-full bg-[#040F00] text-[32px] font-bold leading-[38.73px] flex justify-center items-center"
          >
            2
          </div>
          <div
            class="w-[84px] absolute -bottom-11 -translate-y-1/2 right-1/2 border border-solid border-[#E8F4F1] translate-x-1/2 h-[84px] text-[#3CFF71] rounded-full bg-[#040F00] text-[32px] font-bold leading-[38.73px] flex justify-center items-center"
          >
            3
          </div>
        </div>
      </div>
      <div
        class="w-full lg:w-[47.5%] flex flex-col items-start lg:gap-y-[199px]"
      >
        <div class="hidden lg:inline-block lg:w-auto w-full">
          <h1
            class="text-[64px] font-bold leading-[96px] text-[#3CFF71] text-left"
          >
            Our <span class="text_gradient">Roadmap</span>
          </h1>
          <p
            class="text-base font-semibold leading-6 w-[70%] text-[#3CFF71] text-left"
          >
            Pepe Is Tired Of Watching Everyone Play Hot Potato With The Endless
            Derivative
          </p>
        </div>
        <div class="lg:w-auto mt-6 w-full">
          <div
            data-aos="fade-up"
            class="py-4 lg:py-[38px] shadow-[0px_0px_6px_0px_#3CFF71] w-full lg:w-[475.42px] inline-block px-5 lg:px-[36px] rounded-[22px] border-[0px,0.5px,0.5px,0.5px] border-solid bg-[#081506] border-[#E8F4F1]"
          >
            <h1
              class="text-[28px] lg:text-5xl font-bold lg:leading-[72px] text-left text-[#3CFF71]"
            >
              Phase 2
            </h1>
            <ul class="flex flex-col mt-[26px] gap-y-[18px]">
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                NTM Listing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                Influencer Calls
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                DexScreener Listing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                Av.ai Listing
              </li>
            </ul>
          </div>
        </div>
        <div class="lg:w-auto inline-block mt-6 lg:hidden w-full">
          <div
            data-aos="fade-up"
            class="py-4 lg:py-[38px] shadow-[0px_0px_6px_0px_#3CFF71] w-full lg:w-[475.42px] inline-block px-5 lg:px-[36px] rounded-[22px] border-[0px,0.5px,0.5px,0.5px] border-solid bg-[#081506] border-[#E8F4F1]"
          >
            <h1
              class="text-[28px] lg:text-5xl font-bold lg:leading-[72px] text-left text-[#3CFF71]"
            >
              Phase 3
            </h1>
            <ul class="flex flex-col mt-[26px] gap-y-[18px]">
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Check />
                </div>
                NTM Listing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                Influencer Calls
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex justify-center items-center"
                >
                  <Close />
                </div>
                DexScreener Listing
              </li>
              <li
                class="flex items-center text-[#3CFF71] gap-x-3 text-base font-semibold leading-6 text-left"
              >
                <div
                  class="w-[29px] h-[29px] green_gradient rounded-full flex items-center justify-center"
                >
                  <Close />
                </div>
                Av.ai Listing
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
