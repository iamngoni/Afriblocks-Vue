<template>
  <div class="relative group">
    <a
      class="xl:px-[12px] xl:py-[10px] lg:px-[11px] lg:py-[24px] lg:text-sm xl:text-md flex items-center"
      href=""
      ><span>
        <div class="group flex flex-col items-center justify-center space-y-3">
          <span class="relative">COMMUNITY</span>
          <div
            class="transition duration-200 ease-in delay-[5ms] w-[20px] transform -translate-x-2 scale-0 group-hover:scale-100 group-hover:translate-x-0 bg-white h-[2px] rounded"
          ></div>
        </div>
      </span>
      <svg
        class="w-4 h-4 ml-2 -mr-1 self-start transition duration-150 ease-in-out transform fill-current group-hover:-rotate-180"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 20 20"
        fill="currentColor"
        aria-hidden="true"
      >
        <path
          fill-rule="evenodd"
          d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
          clip-rule="evenodd"
        />
      </svg>
    </a>

    <div
      class="group-hover:-translate-y-0 group-hover:scale-y-100 transform scale-y-0 transition duration-500 ease-in-out translate-y-6 absolute left-0 top-[30px] pt-4 w-[255px] mt-4 origin-top-left"
      role="menu"
      aria-orientation="vertical"
      aria-labelledby="menu-button"
      tabindex="-2"
    >
      <div
        class="flex flex-col pb-1 bg-white border-t-2 divide-y-[1px] divide-gray-[#eeeeee] shadow-lg rounded-b border-[#30b352] ring-1 ring-black ring-opacity-5 focus:outline-none"
        role="none"
      >
        <!-- Active: "bg-gray-100 text-gray-900", Not Active: "text-[#323232]" -->
        <a
          href="#"
          class="block px-[20px] hover:bg-gray-200 leading-[20px] font-[300] text-[14px] min-h-[45px] py-[12px] text-sm text-[#323232]"
          role="menuitem"
          tabindex="-2"
          id="menu-item-5"
          >FREELANCERS COMMUNITY</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
