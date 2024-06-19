<script lang="ts">
import Button from "../Common/Button.vue";

export default {
  components: {
    Button,
  },
};
</script>
<template id="about" >
  <section class="w-full">
    <div class="w-full flex items-center pt-[104px] container" >
        <div class="w-1/2" >
            <h1 class="text-[64px] font-bold leading-[96px] text-left text_gradient" >Tokenomics</h1>
            <p class="text-2xl font-bold leading-9 text-left text-[#E8F4F1] mt-[36px]" >Token Supply: 375,906,235,908,32</p>
            <ul class="flex flex-col gap-y-6 mt-[36px]" >
                <li class="flex items-center gap-x-5" > 
                    <div class="w-[52px] h-[24px] green_gradient rounded-[24px]">
                    </div>
                    <span class="text-base font-semibold leading-6 text-[#E8F4F1] text-left" > 34% team (lock for 6 months{</span>
                </li>
                <li class="flex items-center gap-x-5" > 
                    <div class="w-[52px] h-[24px] yellow_gradient rounded-[24px]">
                    </div>
                    <span class="text-base font-semibold leading-6 text-[#E8F4F1] text-left" > 10% marketing</span>
                </li>
                <li class="flex items-center gap-x-5" > 
                    <div class="w-[52px] h-[24px] yellow_gradient rounded-[24px]">
                    </div>
                    <span class="text-base font-semibold leading-6 text-[#E8F4F1] text-left" > 30% Lp+ staking Rewards</span>
                </li>
                <li class="flex items-center gap-x-5" > 
                    <div class="w-[52px] h-[24px] green_gradient rounded-[24px]">
                    </div>
                    <span class="text-base font-semibold leading-6 text-[#E8F4F1] text-left" > 30% Airdrop</span>
                </li>
            </ul>
        </div>
        <div class="w-1/2" >
            <img src="../Assets/chart.png" alt="">
        </div>
    </div>
  </section>
</template>

<style scoped></style>
