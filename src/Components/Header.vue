<script lang="ts"  >
 import {LINKS} from "../constants/Links"
 import Button from "../Common/Button.vue";


 export default {
  components: {
    Button,
  }

};

</script>
<template >
  <header class="w-full">
    <div class="w-full pt-[43px] flex justify-between items-center container">
      <a href="#" class="flex items-center" >
        <img src="../assets/logo.svg" alt="pepe" />
        <p class="text-[40px] font-bold leading-[77px] text-left text_gradient" >PepeChat</p>
      </a>
      <ul class="flex gap-x-[52px] items-center" >
         <li>
             <a href="" class="hover_link text-base font-semibold text-[#E8F4F1] leading-6 text-left" >Home</a>
         </li>
         <li>
             <a href="#about" class="hover_link text-base font-semibold text-[#E8F4F1] leading-6 text-left" >About</a>
         </li>
         <li>
             <a href="" class="hover_link text-base font-semibold text-[#E8F4F1] leading-6 text-left" >Product</a>
         </li>
         <li>
             <a href="" class="text-base hover_link font-semibold text-[#E8F4F1] leading-6 text-left" >Product</a>
         </li>
        </ul>
        <Button label="Contact Us" variant="primary" />
    </div>
  </header>
</template>
