<template>
  <main>
    <div
      class="flex py-10 space-y-4 lg:space-y-0 lg:py-0 flex-col items-start lg:items-center lg:flex-row justify-between w-full min-h-[101px] bg-[#1f1f1f]"
    >
      <div class="flex items-center h-full px-10 lg:px-0">
        <div
          class="h-full w-full lg:w-[309px] xl:w-[618px] flex items-center justify-center"
        >
          <p class="text-white">Community Stories</p>
        </div>
        <div class="flex-1"></div>
      </div>
      <div
        class="flex items-start w-full overflow-hidden lg:flex-1 px-10 lg:px-8"
      >
        <carousel
          :items-to-show="1"
          :autoplay="2000"
          :wrap-around="true"
          :transition="3000"
          :pause-autoplay-on-hover="true"
          class="max-w-screen flex items-center w-full"
        >
          <slide
            class="box-border overflow-hidden flex justify-start px-12"
            v-for="(item, index) in Stories"
            :key="index"
          >
            <p class="text-white hover:text-[#2b5030] cursor-pointer">
              {{ item.text }}
            </p>
          </slide>
          <template class="px-8 absolute" #addons>
            <navigation />
          </template>
        </carousel>
      </div>
    </div>
  </main>
</template>

<script>
import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel';
export default {
  components: {
    Carousel,
    Slide,
    Pagination,
    Navigation,
  },
  data() {
    return {
      Stories: [
        {
          text: 'Steps To Becoming A Better Freelance Software Developer',
        },
        {
          text: 'Hiring An Employee vs. Freelancer',
        },
        {
          text: 'Freelance Jobs For College Students',
        },
        {
          text: '5 Annoyances You’ll Face As A Freelancer & How To Overcome Them',
        },
        {
          text: 'Tips For Planning For 2022 ',
        },
        {
          text: 'Types of Business Startup Costs',
        },
        {
          text: '12 Skills That are Vital For Successful Virtual Assistants',
        },
        {
          text: '8 Ways To Improve Communication ',
        },
        {
          text: '4 Tips For Attracting Clients',
        },
        {
          text: 'Why Finding A Freelance Community Is Essential For Freelancers',
        },
        {
          text: 'Best Freelance Jobs For College Students ',
        },
      ],
    };
  },
  methods: {},
};
</script>

<style></style>
