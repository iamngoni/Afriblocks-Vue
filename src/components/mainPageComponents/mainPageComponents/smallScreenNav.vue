<template>
  <label
    for="checkbox"
    class="w-full h-full flex items-center px-[10px] py-[6px]"
  >
    <input id="checkbox" type="checkbox" class="peer sr-only" />
    <svg
      class="block absolute insert-0 peer-checked:hidden w-[20px] h-[20px]"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 14"
    >
      <g
        fill="none"
        fill-rule="evenodd"
        stroke="#ffffff"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        transform="translate(1 1)"
      >
        <path d="M0 6h18M0 0h18M0 12h18" />
      </g>
    </svg>
    <svg
      class="hidden absolute insert-0 peer-checked:block w-[20px] h-[20px]"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 16 14"
    >
      <g
        fill="none"
        fill-rule="evenodd"
        stroke="#ffffff"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        transform="translate(1 1)"
      >
        <path d="M12 0L0 12M0 0l12 12" />
      </g>
    </svg>
    <!-- Mobile Navbar popup / dropdown -->
    <div
      class="lg:hidden px-4 w-screen peer-checked:-translate-y-0 peer-checked:scale-y-100 transform scale-y-0 transition duration-500 ease-in-out translate-y-6 absolute -right-[14px] origin-top-right top-[72px] pt-4 mt-4"
      id="mobile-menu"
    >
      <div
        class="pt-2 pb-3 rounded-b flex flex-col py-1 bg-white border-t-2 divide-y-[1px] divide-gray-[#eeeeee] shadow-lg border-[#30b352] ring-1 ring-black ring-opacity-5 focus:outline-none"
      >
        <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
        <a
          href="#"
          class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] min-h-[45px] py-[12px] text-sm text-[#323232]"
          role="menuitem"
          tabindex="-1"
          id="5"
          >HOME</a
        >
        <a
          href="#"
          class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
          role="menuitem"
          tabindex="-1"
          id="menu-item-1"
          >HOW IT WORKS</a
        >
        <a
          href="#"
          class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
          role="menuitem"
          tabindex="-1"
          id="menu-item-2"
          >BECOME A FREELANCER</a
        >
        <details class="w-full bg-white border cursor-pointer">
          <summary
            class="group open: px-[20px] w-full flex justify-between leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
          >
            <span>COMMUNITY</span>
            <div
              class="bg-green-500 rounded font-bold text-white w-9 text-center h-9 flex items-center justify-center"
            >
              <svg
                class="fill-current opacity-75 w-8 h-8"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
              >
                <path
                  d="M12.95 10.707l.707-.707L8 4.343 6.586 5.757 10.828 10l-4.242 4.243L8 15.657l4.95-4.95z"
                />
              </svg>
            </div>
          </summary>
          <div
            class="flex flex-col py-1 bg-white border-t-2 divide-y-[1px] divide-gray-[#eeeeee] border-[#30b352] ring-1 ring-black ring-opacity-5 focus:outline-none"
          >
            <a
              href="#"
              class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] min-h-[45px] py-[12px] text-sm text-[#323232]"
              role="menuitem"
              tabindex="-1"
              id="5"
              >FREELANCER COMMUNITY</a
            >
          </div>
        </details>
        <a
          href="#"
          class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
          role="menuitem"
          tabindex="-1"
          id="menu-item-2"
          >BLOG</a
        >
        <a
          href="#"
          class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
          role="menuitem"
          tabindex="-1"
          id="menu-item-2"
          >ABOUT US</a
        >

        <details class="w-full bg-white border cursor-pointer">
          <summary
            class="group open: px-[20px] w-full flex justify-between leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
          >
            <span>MORE INFO</span>
            <div
              class="bg-green-500 rounded font-bold text-white w-9 text-center h-9 flex items-center justify-center"
            >
              <svg
                class="fill-current opacity-75 w-8 h-8"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
              >
                <path
                  d="M12.95 10.707l.707-.707L8 4.343 6.586 5.757 10.828 10l-4.242 4.243L8 15.657l4.95-4.95z"
                />
              </svg>
            </div>
          </summary>
          <div
            class="flex flex-col py-1 bg-white border-t-2 divide-y-[1px] divide-gray-[#eeeeee] border-[#30b352] ring-1 ring-black ring-opacity-5 focus:outline-none"
          >
            <a
              href="#"
              class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] min-h-[45px] py-[12px] text-sm text-[#323232]"
              role="menuitem"
              tabindex="-1"
              id="5"
              >WHY AFRIBLOCKS</a
            >
            <a
              href="#"
              class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
              role="menuitem"
              tabindex="-1"
              id="menu-item-1"
              >THE AFRICAN FREELANCER SERIES</a
            >
            <a
              href="#"
              class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
              role="menuitem"
              tabindex="-1"
              id="menu-item-2"
              >OUR TEAM</a
            >
            <a
              href="#"
              class="block px-[20px] leading-[20px] hover:bg-gray-200 font-[300] text-[14px] py-[12px] min-h-[45px] text-sm text-[#323232]"
              role="menuitem"
              tabindex="-1"
              id="menu-item-2"
              >CONTACT US</a
            >
          </div>
        </details>
      </div>
    </div>
  </label>
</template>

<script>
export default {};
</script>

<style scoped>
details > summary::-webkit-details-marker {
  display: none;
}
details summary div svg {
  transform: rotate(0deg);
}

details[open] summary div svg {
  transform: rotate(90deg);
}

details[open] summary ~ * {
  animation: ease-opacity-t-b 10s ease;
}

summary {
  cursor: pointer;
}

details summary div svg {
  transition: all 0.3s;
}
</style>
