<script lang="ts" setup>
import ArrowUp from "../Icons/ArrowUp.vue";
import { ref } from "vue";

export type Props = {
  title: string;
  content: string;
};

const props = defineProps<Props>();

const isOpen = ref(false);

const handleOpen = () => {
  isOpen.value = !isOpen.value;
};
</script>

<template>
  <div
    @click="handleOpen"
    class="w-full min-h-[80px] relative cursor-pointer rounded-[12px] px-0 lg:px-[30px] border border-solid"
    :class="[
      isOpen ? 'border-[#3CFF71] py-10 ' : 'border-[#E8F4F1]  py-[28px] ',
    ]"
  >
    <div class="flex items-center justify-between w-full">
      <div>
        <p
          class="[&quot; text-[14px] px-4 lg:text-base font-semibold text-[#E8F4F1] leading-6 text-left&quot;] absolute top-1/2 transition-all duration-300 -translate-y-1/2 z-10"
          :class="[
            isOpen ? '!top-0 !text-[14px] !z-10 bg-[#040f00] text-white ' : '',
          ]"
        >
          {{ props.title }}
        </p>
      </div>
      <div
        class="transition-all absolute top-1/2 -translate-y-1/2 right-2 lg:right-[51px] duration-300"
        :class="[isOpen ? 'rotate-180' : 'rotate-0']"
      >
        <ArrowUp class="text-[#E8F4F1]" />
      </div>
    </div>
    <div
      class="text-[12px] w-[80%] pl-4 lg:pl-0 lg:text-base font-semibold lg:leading-6 lg:w-[60%] text-left text-[#E8F4F1] overflow-hidden transition-all duration-200"
      :class="[isOpen ? 'h-auto' : 'h-0']"
    >
      {{ props.content }}
    </div>
  </div>
</template>
