<script lang="ts" setup >
export type Props = {
    class?: string
};

const props = defineProps<Props>();

</script>
<template>
  <svg
    width="111"
    height="111"
    viewBox="0 0 111 111"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    :class="props.class"
  >
    <g filter="url(#filter0_bd_96_22)">
      <rect
        x="12"
        y="9"
        width="87"
        height="87"
        rx="43.5"
        fill="white"
        fill-opacity="0.67"
        shape-rendering="crispEdges"
      />
      <rect
        x="11.5956"
        y="8.59562"
        width="87.8088"
        height="87.8088"
        rx="43.9044"
        stroke="black"
        stroke-opacity="0.06"
        stroke-width="0.808765"
        shape-rendering="crispEdges"
      />
      <g clip-path="url(#clip0_96_22)">
        <path
          d="M66.9895 48.7405L45.1206 34.7791V70.2772L66.9806 56.2669C67.6169 55.8669 68.1415 55.3122 68.5054 54.6545C68.8693 53.9969 69.0606 53.2577 69.0615 52.5061C69.0624 51.7545 68.8728 51.0149 68.5105 50.3564C68.1482 49.6979 67.6249 49.142 66.9895 48.7405Z"
          fill="#3E3E3E"
        />
      </g>
    </g>
    <defs>
      <filter
        id="filter0_bd_96_22"
        x="0.677463"
        y="-2.32272"
        width="109.645"
        height="112.881"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix" />
        <feGaussianBlur in="BackgroundImageFix" stdDeviation="5.25697" />
        <feComposite
          in2="SourceAlpha"
          operator="in"
          result="effect1_backgroundBlur_96_22"
        />
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        />
        <feOffset dy="3.23506" />
        <feGaussianBlur stdDeviation="5.25697" />
        <feComposite in2="hardAlpha" operator="out" />
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.16 0"
        />
        <feBlend
          mode="normal"
          in2="effect1_backgroundBlur_96_22"
          result="effect2_dropShadow_96_22"
        />
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="effect2_dropShadow_96_22"
          result="shape"
        />
      </filter>
      <clipPath id="clip0_96_22">
        <rect
          width="35.5857"
          height="35.5857"
          fill="white"
          transform="translate(37.707 34.7072)"
        />
      </clipPath>
    </defs>
  </svg>
</template>
