<script lang="ts">
import Button from "../Common/Button.vue";
import { ref, watch } from "vue";

export default {
  components: {
    Button,
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
      </ul>
      <Button
        class="lg:inline-block z-10 hidden"
        label="Contact Us"
        variant="primary"
      />
      <div
        @click="closeMenu"
        class="w-[45px] h-[30px] z-[999] flex lg:hidden flex-col justify-between cursor-pointer"
      >
        <div class="w-full h-[3px] rounded bg-white" />
        <div class="w-full h-[3px] rounded bg-white" />
        <div class="w-full h-[3px] rounded bg-white" />
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
