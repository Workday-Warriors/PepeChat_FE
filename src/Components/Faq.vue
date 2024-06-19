<script lang="ts">
import Button from "../Common/Button.vue";
import Accordion from "../Common/Accardion.vue";
export default {
  components: {
    Button,
    Accordion,
  },
};
</script>
<template id="about">
  <section class="w-full">
    <div class="w-full container pt-[163px]">
    <h1 class="text-[64px] font-bold leading-[77px] text-center text_gradient" >F.A.Q</h1>
    <div class="flex flex-col gap-y-6 mt-[92px]" >
        <Accordion title="1. What services does your pepe chat offer?" content="Customers often want a clear understanding of the services provided, whether it's web design, branding, social media management, content creation, or digital marketing strategies." />
        <Accordion title="2. Why pepe chat is different than others?" content="Customers often want a clear understanding of the services provided, whether it's web design, branding, social media management, content creation, or digital marketing strategies." />
        <Accordion title="3. What is your working process?" content="Customers often want a clear understanding of the services provided, whether it's web design, branding, social media management, content creation, or digital marketing strategies." />
        <Accordion title="4. How to buy pepe chat?" content="Customers often want a clear understanding of the services provided, whether it's web design, branding, social media management, content creation, or digital marketing strategies." />
        <Accordion title="5. About pepe chat?" content="Customers often want a clear understanding of the services provided, whether it's web design, branding, social media management, content creation, or digital marketing strategies." />
    </div>
    </div>
  </section>
</template>

<style scoped></style>
