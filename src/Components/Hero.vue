<script lang="ts">
import Button from "../Common/Button.vue";

export default {
    components: {
        Button,
    },
};
</script>
<template>
    <section class="w-full">
        <div class="w-full pt-[138px] container flex">
            <div class="w-1/2">
                <h1 class="text-[80px] font-bold leading-[92px] text-left text-[#E8F4F1]"><span
                        class="text_gradient">PepeChat:</span> Expert Advice Real-Time Chat</h1>
                <p class="text-base font-semibold py-[36px] text-[#C3C3C3] leading-6 text-left">
                    Our chat website connects you with fellow Pepe enthusiasts and
                    experts. Ask questions and share knowledge about rare Pepes, meme
                    history, and responsible collecting. Test your Pepe IQ with quizzes
                    and fun games, or even unleash your creativity by designing your own
                    Pepe art. We prioritize a safe and respectful chat environment with
                    clear guidelines and moderation.
                </p>
                <div class="flex gap-x-6">
                    <Button label="Buy Now!" variant="primary" />
                    <Button label="Chat Now!" variant="outline" />
                </div>
            </div>
            <div class="w-1/2">
                <img class="w-full object-cover" src="../Assets/hero-image.png" alt="PepeChat" />
            </div>
        </div>
        <div class="w-full container mt-[41px]">
            <div class="border_gradient w-full rounded-[8px]">
                <div class="w-full grid grid-cols-4 shadow-[0px_0px_8px_0px_#56FF7B59] rounded-[8px] ">
                    <div class="border_right_gradient py-10" >
                        <h3 class="text-4xl font-bold leading-[54px] text-center text_gradient">8</h3>
                        <p class="text-xl font-bold leading-[30px] text-center text_gradient">Taxers</p>
                    </div>
                    <div class="border_right_gradient py-10" >
                        <h3 class="text-4xl font-bold leading-[54px] text-center text_gradient">7523</h3>
                        <p class="text-xl font-bold leading-[30px] text-center text_gradient">Holders</p>
                    </div>
                    <div class="border_right_gradient py-10"  >
                        <h3 class="text-4xl font-bold leading-[54px] text-center text_gradient">854</h3>
                        <p class="text-xl font-bold leading-[30px] text-center text_gradient">Most Pepe</p>
                    </div>
                    <div class="py-10">
                        <h3 class="text-4xl font-bold leading-[54px] text-center text_gradient">854</h3>
                        <p class="text-xl font-bold leading-[30px] text-center text_gradient">Most Pepe</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<style scoped>
.border_right_gradient {
    position: relative;
}
.border_right_gradient::before{
    content: "";
    position: absolute;
    right: 0px;
    top: 0px;
    width: 2px;
    height: 100%;
    background: linear-gradient(90deg, #0A2D0E -0.87%, #3CFF71 51.51%, #061703 100%);
    border-radius: 250% !important;
}
</style>