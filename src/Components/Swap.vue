<script lang="ts">
import Button from "../Common/Button.vue";

export default {
  components: {
    Button,
  },
};
</script>
<template>
  <section class="w-full relative">
    <div
      data-aos="fade-up"
      class="w-full container flex-col lg:flex-row gap-y-10 lg:flex items-center pt-[24px] lg:pt-[117px]"
    >
      <div class="w-full lg:w-1/2">
        <h3
          data-aos="fade-up"
          class="text-[32px] lg:text-[40px] font-bold text-left text_gradient"
        >
          PepeChat
        </h3>
        <h1
          data-aos="fade-up"
          class="text-[32px] lg:text-[64px] font-bold text-left text-[#E8F4F1]"
        >
          Decentral 12ed <span class="text_gradient">Exchange Token</span>
        </h1>
        <p
          data-aos="fade-up"
          class="text-base font-semibold mt-9 leading-6 text-left text-[#C3C3C3]"
        >
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat.
        </p>
      </div>
      <div class="w-full lg:w-1/2 flex justify-center items-center">
        <div
          class="w-full lg:w-[561px] mt-10 py-4 lg:py-[31px] px-3 lg:px-[41px] rounded-[15px] border border-solid border-[#3CFF71] shadow-[0px_0px_21px_0px_#3CFF71]"
        >
          <div class="flex w-full justify-between">
            <h1
              data-aos="fade-up"
              class="text-xl font-bold leading-[30px] text-left text-[#E8F4F1]"
            >
              Swap
            </h1>
            <div
              data-aos="fade-up"
              class="px-[15px] py-[1px] rounded-[100px] text-[#E8F4F1] border text-[10px] font-bold leading-6 text-left border-[#3dff71]"
            >
              3%
            </div>
          </div>
          <div class="flex flex-col mt-4 gap-y-5">
            <div
              data-aos="fade-up"
              class="bg-[#061604] px-[10px] py-[15px] rounded-[9px] border-b-[0.5px] border-b-[#C5FFA9] border-solid"
            >
              <div class="flex items-center justify-between">
                <div class="flex items-center">
                  <img src="../Assets/coin-1.png" class="w-[34px] h-[34px]" />
                  <select
                    value="ETH"
                    class="bg-transparent ml-4 mr-9 outline-none border-none text-[#E8F4F1] text-xs font-semibold leading-[16.34px] text-left"
                  >
                    <option value="PEPE">PEPE</option>
                    <option value="ETH">ETH</option>
                  </select>
                  <div
                    class="px-3 py-[6px] rounded-[100px] green_gradient text-[8px] font-bold leading-[10.89px] text-left"
                  >
                    MAX
                  </div>
                </div>
                <div>
                  <p
                    class="text-xs font-bold leading-[16.34px] text-left text_gradient"
                  >
                    Balance
                  </p>
                  <p
                    class="text-[10px] font-semibold leading-[13.62px] text-left text-[#E8F4F1]"
                  >
                    0.00002
                  </p>
                </div>
              </div>
            </div>

            <div
              data-aos="fade-up"
              class="bg-[#061604] px-[10px] py-[15px] rounded-[9px] border-b-[0.5px] border-b-[#C5FFA9] border-solid"
            >
              <div class="flex items-center justify-between">
                <div class="flex items-center">
                  <img src="../Assets/coin-1.png" class="w-[34px] h-[34px]" />
                  <select
                    value="PEPE"
                    class="bg-transparent ml-4 mr-9 outline-none border-none text-[#E8F4F1] text-xs font-semibold leading-[16.34px] text-left"
                  >
                    <option value="PEPE">PEPE</option>
                    <option value="ETH">ETH</option>
                  </select>
                  <div
                    class="px-3 py-[6px] rounded-[100px] green_gradient text-[8px] font-bold leading-[10.89px] text-left"
                  >
                    MAX
                  </div>
                </div>
                <div>
                  <p
                    class="text-xs font-bold leading-[16.34px] text-left text_gradient"
                  >
                    Balance
                  </p>
                  <p
                    class="text-[10px] font-semibold leading-[13.62px] text-left text-[#E8F4F1]"
                  >
                    0.00002
                  </p>
                </div>
              </div>
            </div>

            <p
              class="text-[8px] font-normal leading-[15px] text-[#E8F4F1] text-right"
            >
              *All fees included in price quote
            </p>
            <h4 class="text-sm font-bold leading-6 text-left text-[#E8F4F1]">
              Best Price
            </h4>
            <div
              data-aos="fade-up"
              class="grid grid-cols-1 gap-y-2 lg:grid-cols-5 gap-x-6"
            >
              <Button
                label="Price Impact 0.06"
                variant="outline"
                class="col-span-1 lg:col-span-2"
              />
              <Button
                label="Enter Amount"
                variant="primary"
                class="col-span-1 lg:col-span-3"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="green_blur hidden lg:inline-block w-[1134px] h-[1134px] absolute top-[-600px] right-[-700px]"
    />
  </section>
</template>
