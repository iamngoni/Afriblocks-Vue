<template>
  <main class="bg-[#1a1a1a] py-8">
    <div class="min-h-[80px] mb-[50px]">
      <div class="w-full text-center">
        <p
          class="text-white text-[36px] font-[300] leading-[48px] text-center py-[10px]"
        >
          Partners
        </p>
      </div>
    </div>
    <div
      class="flex items-start w-full overflow-hidden lg:flex-1 px-10 lg:px-8 py-8"
    >
      <carousel
        :items-to-show="4"
        :autoplay="2000"
        :wrap-around="true"
        :transition="3000"
        :pause-autoplay-on-hover="true"
        class="w-full hidden md:block"
      >
        <slide
          class="box-border overflow-hidden flex"
          v-for="(item, index) in Partners"
          :key="index"
        >
          <img class="block w-[144px] h-[144px]" :src="item.src" />
        </slide>
      </carousel>
      <carousel
        :items-to-show="1"
        :autoplay="2000"
        :wrap-around="true"
        :transition="3000"
        :pause-autoplay-on-hover="true"
        class="w-full block md:hidden"
      >
        <slide
          class="box-border overflow-hidden flex"
          v-for="(item, index) in Partners"
          :key="index"
        >
          <img class="block w-[144px] h-[144px]" :src="item.src" />
        </slide>
      </carousel>
    </div>
    <div class="w-full flex items-center justify-center bg-[#1f1f1f]">
      <div
        class="flex flex-col space-y-8 lg:space-y-0 lg:flex-row items-center w-full lg:w-3/4 justify-center py-8"
      >
        <div class="flex flex-col items-center justify-center w-full lg:w-1/2">
          <span
            class="text-[36px] text-white leading-[36px] font-[300] mb-[10px]"
            >Ubuntu</span
          >
          <p class="text-[18px] text-white leading-[22px] font-[300]">
            We have made it easy to work together
          </p>
          <div class="w-[170px] h-[4px] rounded bg-[#30b352] mt-[20px]"></div>
          <TypeWritterEffect
            class="mt-8"
            title="#Connecting"
            :words="['People', 'Cultures', 'Professionals']"
          />
        </div>
        <div
          class="w-full lg:w-1/2 flex items-center justify-center lg:block px-8 lg:px-0"
        >
          <iframe
            class="aspect-video max-w-[570px] mx-h-[244px] sm:w-[570px]"
            src="https://www.youtube.com/embed/wvzpDYXfaEk"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel';
import TypeWritterEffect from './mainPageComponents/typeWritterEffect.vue';
import image1 from '../../assets/Partners/Google-For-Startups-150x150.png';
import image2 from '../../assets/Partners/Transparent-Collective-150x150.png';
import image3 from '../../assets/Partners/Untitled-design-3-150x150.png';
import image4 from '../../assets/Partners/Untitled-design-4-150x150.png';

export default {
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
    TypeWritterEffect,
  },
  data() {
    return {
      Partners: [
        {
          src: image1,
        },
        {
          src: image2,
        },
        {
          src: image3,
        },
        {
          src: image4,
        },
        {
          src: image1,
        },
        {
          src: image2,
        },
        {
          src: image3,
        },
        {
          src: image4,
        },
      ],
    };
  },
  methods: {},
};
</script>

<style></style>
