<script lang="ts">
import Button from "../Common/Button.vue";
import { ref, watch } from "vue";
import Twitter from "../Icons/Twitter.vue";
import Telegram from "../Icons/Telegram.vue";
import Discord from "../Icons/Discord.vue";
import Instagram from "../Icons/Instagram.vue";

export default {
  components: {
    Button,
    Twitter,
    Telegram,
    Discord,
    Instagram,
  },
  setup() {
    const isOpen = ref<boolean>(false);

    const toggleMenu = () => {
      isOpen.value = !isOpen.value;
    };

    const closeMenu = () => {
      isOpen.value = false;
    };

    watch(isOpen, (newVal) => {
      if (newVal) {
        document.body.style.overflow = "hidden";
      } else {
        document.body.style.overflow = "auto";
      }
    });

    return {
      isOpen,
      toggleMenu,
      closeMenu,
    };
  },
};
</script>

<template>
  <header class="w-full">
    <div
      class="w-full pt-5 px-4 lg:px-8 lg:pt-[43px] flex justify-between items-center container"
    >
      <a href="#" class="flex items-center">
        <img src="../assets/logo.svg" alt="pepe" />
        <p
          class="text-[40px] hidden lg:inline-block font-bold leading-[77px] text-left text_gradient"
        >
          PepeChat
        </p>
      </a>
      <ul
        :class="[isOpen ? 'left-0' : 'left-[-100%]']"
        class="fixed flex-col top-0 bg-[#040f00] lg:bg-transparent z-[99] pt-20 lg:pt-0 pl-10 gap-y-5 lg:gap-y-0 lg:pl-0 items-start w-full h-full lg:w-auto lg:h-auto lg:flex-row lg:static flex gap-x-[52px] lg:items-center transition-all duration-300"
      >
        <li>
          <a
            @click="closeMenu"
            href="#"
            class="hover_link text-base font-semibold text-[#E8F4F1] leading-6 text-left"
            >Home</a
          >
        </li>
        <li>
          <a
            @click="closeMenu"
            href="#about"
            class="hover_link text-base font-semibold text-[#E8F4F1] leading-6 text-left"
            >About</a
          >
        </li>
        <li>
          <a
            @click="closeMenu"
            href="#products"
            class="hover_link text-base font-semibold text-[#E8F4F1] leading-6 text-left"
            >Product</a
          >
        </li>
        <li>
          <a
            @click="closeMenu"
            href="#roadmap"
            class="text-base hover_link font-semibold text-[#E8F4F1] leading-6 text-left"
            >Roadmap</a
          >
        </li>
        <li class="inline-block lg:hidden">
          <Button label="Contact Us" variant="primary" />
        </li>
        <div class="absolute inline-block lg:hidden bottom-10">
          <div
            class="flex justify-center gap-x-4 lg:gap-x-[44px] mt-5 lg:mt-[63px]"
          >
            <a
              href="#s"
              class="w-[42.86px] icon_hover hover:text-[#040F00] h-[42.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
            >
              <Twitter />
            </a>
            <a
              href="#"
              class="w-[42.86px] icon_hover hover:text-[#040F00] h-[42.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
            >
              <Telegram />
            </a>
            <a
              href="#"
              class="w-[42.86px] icon_hover hover:text-[#040F00] h-[42.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
            >
              <Discord />
            </a>
            <a
              href="#"
              class="w-[42.86px] icon_hover hover:text-[#040F00] h-[42.86px] rounded-full border border-[#3CFF71] text-[#3CFF71] flex justify-center items-center"
            >
              <Instagram />
            </a>
          </div>
        </div>
      </ul>
      <Button
        class="lg:inline-block z-10 hidden"
        label="Contact Us"
        variant="primary"
      />
      <div
        @click="toggleMenu"
        class="w-[35px] h-[26px] z-[999] flex lg:hidden flex-col justify-between cursor-pointer"
      >
        <div
          :class="[
            'w-full h-[3px] rounded bg-white transition-transform duration-300',
            isOpen ? 'transform rotate-[46deg] translate-y-[13px]' : '',
          ]"
        />
        <div
          :class="[
            'w-full h-[3px] rounded bg-white transition-opacity duration-300',
            isOpen ? 'opacity-0' : '',
          ]"
        />
        <div
          :class="[
            'w-full h-[3px] rounded bg-white transition-transform duration-300',
            isOpen ? 'transform -rotate-[46deg] -translate-y-[10px]' : '',
          ]"
        />
      </div>
    </div>
    <div
      class="green_blur hidden lg:inline-block w-[1134px] h-[1134px] absolute top-0 left-[-700px]"
    />
    <div
      class="green_blur hidden lg:inline-block w-[1134px] h-[1134px] absolute top-[-600px] right-[-700px]"
    />
  </header>
</template>
