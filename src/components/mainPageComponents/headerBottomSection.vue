<template>
  <main class="bg-[#1a1a1a]">
    <div
      class="flex items-center py-10 lg:py-0 flex-col lg:flex-row justify-between w-full min-h-[150px]"
    >
      <div class="flex items-center h-full">
        <div
          class="h-full w-full lg:w-[618px] flex items-center justify-center"
        >
          <p class="font-[700] text-[#414141] text-[14px] leading-[20px]">
            As Featured In:
          </p>
        </div>
        <div class="flex-1"></div>
      </div>
      <div class="flex items-start w-full overflow-hidden lg:flex-1">
        <carousel
          :items-to-show="4"
          :autoplay="1"
          :wrap-around="true"
          :transition="3000"
          class="max-w-screen hidden lg:block w-full"
        >
          <slide
            class="box-border overflow-hidden flex"
            v-for="(item, index) in images"
            :key="index"
          >
            <img class="block w-[144px] h-[144px]" :src="item.src" />
          </slide>
        </carousel>
        <carousel
          :items-to-show="1"
          :autoplay="2000"
          :wrap-around="true"
          :transition="5000"
          class="max-w-screen block lg:hidden w-full py-16"
        >
          <slide
            class="box-border overflow-hidden flex"
            v-for="(item, index) in images"
            :key="index"
          >
            <img class="block w-[144px] h-[144px]" :src="item.src" />
          </slide>
        </carousel>
      </div>
    </div>
    <div class="w-full py-[20px] flex flex-col lg:flex-row items-center">
      <div
        class="flex flex-col w-full lg:w-1/2 items-center space-y-[20px] p-[10px]"
      >
        <img src="../../assets/developers20./1-2-768x195.jpg" alt="" />
        <button
          class="bg-[#30b352] group text-white hover:bg-[#6ce812] transition duration-500 ease-in w-[178px] h-[48px] text-[16px] font-[300] leading-[16px] px-[15px] rounded-[2px]"
        >
          <div class="block transition duration-500 ease-in group-hover:hidden">
            Work With Them
          </div>
          <div class="hidden transition duration-500 ease-in group-hover:block">
            Read More
          </div>
        </button>
      </div>
      <div
        class="flex flex-col lg:w-1/2 items-center w-full space-y-[20px] p-[10px]"
      >
        <img src="../../assets/developers20./2-2-768x195.jpg" alt="" />
        <button
          class="bg-[#30b352] group text-white hover:bg-[#6ce812] transition duration-500 ease-in w-[178px] h-[48px] text-[16px] font-[300] leading-[16px] px-[15px] rounded-[2px]"
        >
          <div class="block transition duration-500 ease-in group-hover:hidden">
            Work With Them
          </div>
          <div class="hidden transition duration-500 ease-in group-hover:block">
            Read More
          </div>
        </button>
      </div>
    </div>
  </main>
</template>

<script>
import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel';
import image1 from '../../assets/companiesSlider/AfroTech-150x150.png';
import image2 from '../../assets/companiesSlider/Disrupt-Africa-150x150.png';
import image3 from '../../assets/companiesSlider/GeekWire-150x150.png';
import image4 from '../../assets/companiesSlider/TechCrunch-150x150.png';
import image5 from '../../assets/companiesSlider/TechZim-150x150.png';

export default {
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
  },
  data() {
    return {
      images: [
        {
          src: image1,
          alt: '',
        },
        {
          src: image2,
          alt: '',
        },
        {
          src: image3,
          alt: '',
        },
        {
          src: image4,
          alt: '',
        },
        {
          src: image5,
          alt: '',
        },
        {
          src: image1,
          alt: '',
        },
        {
          src: image2,
          alt: '',
        },
        {
          src: image3,
          alt: '',
        },
        {
          src: image4,
          alt: '',
        },
        {
          src: image5,
          alt: '',
        },
        {
          src: image1,
          alt: '',
        },
        {
          src: image2,
          alt: '',
        },
        {
          src: image3,
          alt: '',
        },
        {
          src: image4,
          alt: '',
        },
        {
          src: image5,
          alt: '',
        },
      ],
    };
  },
  methods: {},
};
</script>

<style></style>
