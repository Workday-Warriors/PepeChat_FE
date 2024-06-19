<script lang="ts" setup>
export type Props = {
  label: string;
  onClick?: () => void;
  variant?: "primary"  | "outline";
};

const props = defineProps<Props>();

const buttonClass = () => {
  switch (props.variant) {
    case "primary":
      return "border-[#1F3717] button_bg text-[#040F00]";
    case "outline":
      return "border-[#E8F4F1] text-[#E8F4F1] button_outline";
  }
};

</script>

<template>
  <button
    :class="['px-6 py-3 rounded-[8px] border text-base font-semibold leading-6 text-center', buttonClass()]"
    @click="props.onClick"
  >
    {{ props.label }}
  </button>
</template>
