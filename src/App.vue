<script setup lang="ts">
import Header from "./Components/Header.vue";
import Hero from "./Components/Hero.vue";
import About from "./Components/About.vue";
import HowToBuy from "./Components/HowToBuy.vue";
import Tokenomics from "./Components/Tokenomics.vue";
import Swap from "./Components/Swap.vue";
import Roadmap from "./Components/Roadmap.vue";
import Footer from "./Components/Footer.vue";
import Faq from "./Components/Faq.vue";
import { onMounted } from "vue";
import AOS from "aos";

onMounted(() => {
  AOS.init({
    duration: 1000,
    easing: "ease",
    once: true,
    offset: 200,
  });
});
</script>

<template>
  <Header />
  <Hero />
  <About />
  <HowToBuy />
  <Swap />
  <Tokenomics />
  <Roadmap />
  <Faq />
  <Footer />
</template>

<style scoped></style>
