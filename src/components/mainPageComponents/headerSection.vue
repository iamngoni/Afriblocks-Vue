<template>
  <main>
    <div class="bg-[#1f1d1d] w-full h-[876px]">
      <!--      <div class="w-full h-[876px]">
        <img class="w-full h-[876px]" :src="currentImageLink" alt="" />
      </div> -->
      <div
        class="w-full h-[876px] flex flex-col bg-cover bg-no-repeat"
        :style="{ 'background-image': 'url(' + currentImageLink + ')' }"
      >
        <nav
          class="flex bg-[#1f1f1f5c] justify-between items-center flex-row lg:flex-col lg:items-start xl:flex-row lg:justify-between border-b px-[15px] border-gray-500"
        >
          <div>
            <img
              src="../../assets/Afriblocks-Logo-Final-04.png"
              alt=""
              class="w-[129] h-[99.65px] object-cover"
            />
          </div>
          <div
            class="relative flex space-x-2 text-white lg:self-end xl:self-center lg:py-0"
          >
            <ul
              class="relative hidden space-x-2 lg:flex lg:space-x-1 xl:space-x-2 items-start"
            >
              <a
                class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md flex flex-col items-center"
                href=""
              >
                <div
                  class="flex flex-col items-center justify-center space-y-3"
                >
                  <span class="relative">HOME</span>
                  <div class="w-[20px] bg-white h-[2px] rounded"></div>
                </div> </a
              ><a
                class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md"
                href=""
              >
                <div
                  class="group flex flex-col items-center justify-center space-y-3"
                >
                  <span class="relative">HOW IT WORKS</span>
                  <div
                    class="transition duration-200 ease-in delay-[5ms] w-[20px] transform -translate-x-2 scale-0 group-hover:scale-100 group-hover:translate-x-0 bg-white h-[2px] rounded"
                  ></div>
                </div> </a
              ><a
                class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md"
                href=""
              >
                <div
                  class="group flex flex-col items-center justify-center space-y-3"
                >
                  <span class="relative">BECOME A FREELANCER</span>
                  <div
                    class="transition duration-200 ease-in delay-[5ms] w-[20px] transform -translate-x-2 scale-0 group-hover:scale-100 group-hover:translate-x-0 bg-white h-[2px] rounded"
                  ></div></div></a
              ><a
                class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md"
                href=""
              >
                <div
                  class="group flex flex-col items-center justify-center space-y-3"
                >
                  <span class="relative">GET WORK DONE</span>
                  <div
                    class="transition duration-200 ease-in delay-[5ms] w-[20px] transform -translate-x-2 scale-0 group-hover:scale-100 group-hover:translate-x-0 bg-white h-[2px] rounded"
                  ></div>
                </div>
              </a>
              <CommunityDropdown />
              <a
                class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md"
                href=""
              >
                <div
                  class="group flex flex-col items-center justify-center space-y-3"
                >
                  <span class="relative">BLOG</span>
                  <div
                    class="transition duration-200 ease-in delay-[5ms] w-[20px] transform -translate-x-2 scale-0 group-hover:scale-100 group-hover:translate-x-0 bg-white h-[2px] rounded"
                  ></div></div></a
              ><a
                class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md"
                href=""
              >
                <div
                  class="group flex flex-col items-center justify-center space-y-3"
                >
                  <span class="relative">ABOUT US</span>
                  <div
                    class="transition duration-200 ease-in delay-[5ms] w-[20px] transform -translate-x-2 scale-0 group-hover:scale-100 group-hover:translate-x-0 bg-white h-[2px] rounded"
                  ></div></div
              ></a>
              <!-- more info link -->
              <MoreInfoDropdown />
            </ul>

            <div
              class="flex items-center justify-center lg:hidden w-[42px] bg-[#30b352] rounded-[4px] h-[36px]"
            >
              <!-- small screen element/link -->
              <SmallScreenNav />
            </div>

            <button
              class="bg-[#30b352] w-[100px] h-[36px] text-[13px] font-[700] leading-[36px] px-[15px] rounded-[4px] self-center mb-4"
            >
              Join Now
            </button>
          </div>
        </nav>
        <div
          class="flex bg-[#1f1f1f5c] flex-col items-center justify-center flex-1"
        >
          <p
            class="text-white text-[40px] font-[400] leading-[40px] text-center mb-[19px]"
          >
            Build Better
          </p>
          <p
            class="text-white text-[40px] font-[600] leading-[50px] text-center mb-[19px]"
          >
            With Qualified, Affordable
          </p>
          <p
            class="text-white text-[40px] font-[600] leading-[50px] text-center mb-[19px]"
          >
            Freelancers
          </p>
          <p
            class="text-white text-[18px] font-[100] leading-[28px] text-center mb-[20px]"
          >
            The Global Pan-African Freelance Marketplace
          </p>
          <button
            class="bg-[#30b352] group text-white hover:bg-[#6ce812] transition duration-500 ease-in w-[150px] h-[53px] text-[16px] font-[300] leading-[16px] px-[15px] rounded-[2px]"
          >
            <div
              class="block transition duration-500 ease-in group-hover:hidden"
            >
              Post A Job
            </div>
            <div
              class="hidden transition duration-500 ease-in group-hover:block"
            >
              Get Started
            </div>
          </button>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import SmallScreenNav from './mainPageComponents/smallScreenNav.vue';
import MoreInfoDropdown from './mainPageComponents/moreInfoDropdown.vue';
import CommunityDropdown from './mainPageComponents/communityDropdown.vue';
export default {
  components: {
    SmallScreenNav,
    MoreInfoDropdown,
    CommunityDropdown,
  },
  data() {
    return {
      isActive: false,
      images: [
        {
          src: 'https://afriblocks.com/wp-content/uploads/2021/05/AfriBlocks-Banner-01.jpg',
          alt: '',
        },
        {
          src: 'https://afriblocks.com/wp-content/uploads/2021/05/AfriBlocks-Banner.jpg',
          alt: '',
        },
      ],
      currentImage: 0,
      currentImageLink: '',
    };
  },
  mounted() {
    this.startSlideShow();
  },
  computed: {
    currentImageLink() {
      return this.images[this.currentImage].src;
    },
  },
  methods: {
    startSlideShow() {
      this.currentImage = 0;
      this.currentImageLink = this.images[this.currentImage].src;
      this.isActive = true;
      this.slideShow();
    },
    slideShow() {
      if (this.isActive) {
        this.currentImage++;
        if (this.currentImage >= this.images.length) {
          this.currentImage = 0;
        }
        this.currentImageLink = this.images[this.currentImage].src;
        setTimeout(this.slideShow, 5000);
      }
    },
    stopSlideShow() {
      this.isActive = false;
    },
  },
};
</script>

<style scoped></style>
