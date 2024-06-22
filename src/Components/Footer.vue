<script setup lang="ts">
import Twitter from '../Icons/Twitter.vue'
import Telegram from '../Icons/Telegram.vue'
import Discord from '../Icons/Discord.vue'
import Instagram from '../Icons/Instagram.vue'
</script>

<template>
  <footer class="w-full relative">
    <div class="container footer_border pb-[38px] w-full">
      <h1
        class="text-[32px] lg:text-[64px] font-bold lg:leading-[77px] mt-6 lg:mt-[221px] text-[#E8F4F1] text-center"
      >
        Join Our <span class="text_gradient">Community</span>
      </h1>
      <div
        class="flex justify-center gap-x-4 lg:gap-x-[44px] mt-5 lg:mt-[63px]"
      >
        <a
          href="#s"
          class="w-[62.86px] icon_hover hover:text-[#040F00] h-[62.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
        >
          <Twitter />
        </a>
        <a
          href="#"
          class="w-[62.86px] icon_hover hover:text-[#040F00] h-[62.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
        >
          <Telegram />
        </a>
        <a
          href="#"
          class="w-[62.86px] icon_hover hover:text-[#040F00] h-[62.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
        >
          <Discord />
        </a>
        <a
          href="#"
          class="w-[62.86px] icon_hover hover:text-[#040F00] h-[62.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
        >
          <Instagram />
        </a>
      </div>
    </div>
    <div class="container py-6">
      <div class="flex gap-x-[15px]">
        <a
          href="#"
          class="text-xs text-[#E8F4F1] !underline font-semibold leading-[16.34px] text-center transition-all duration-300 hover:!underline hover_link"
          >Privacy Policy</a
        >
        <a
          href="#"
          class="text-xs text-[#E8F4F1] !underline font-semibold leading-[16.34px] text-center transition-all duration-300 hover:!underline hover_link"
          >Cookie Policy</a
        >
      </div>
    </div>
    <div
      class="hidden lg:inline-block green_blur w-[1134px] h-[1134px] absolute top-[-600px] right-[-900px]"
    />
  </footer>
</template>
