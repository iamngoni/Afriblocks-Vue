<template>
  <main class="bg-[#1f1f1f] py-8">
    <div class="min-h-[170px] flex items-center">
      <div class="flex flex-col items-center justify-center w-full">
        <p
          class="text-white text-[36px] font-[300] leading-[48px] text-center py-[10px]"
        >
          How it Works
        </p>
        <p
          class="text-[#919191] text-[20px] font-[100] leading-[20px] text-center"
        >
          We Make it Easy, No Headaches
        </p>
      </div>
    </div>
    <div
      class="flex flex-col items-center space-y-8 space-x-0 lg:space-y-0 justify-center lg:flex-row lg:justify-center lg:space-x-12 py-[30px]"
    >
      <div
        class="h-[230] min-w-[379] flex flex-col items-center justify-center"
      >
        <img src="../../assets/HowItWorks/job-offer-1-100x100.png" alt="" />
        <p
          class="text-white text-[20px] font-[300] leading-[20px] text-center py-[10px]"
        >
          Post A Job
        </p>
        <p
          class="text-[#acaaaa] text-[15px] font-[200] leading-[20px] text-center mb-[20px]"
        >
          We will connect you with the right vetted freelancer for the job
        </p>
      </div>
      <div
        class="h-[230] min-w-[379] flex flex-col items-center justify-center"
      >
        <img
          src="../../assets/HowItWorks/project-management-1-100x100.png"
          alt=""
        />
        <p
          class="text-white text-[20px] font-[300] leading-[20px] text-center py-[10px]"
        >
          Project Management
        </p>
        <p
          class="text-[#acaaaa] text-[15px] font-[200] leading-[20px] text-center mb-[20px]"
        >
          Get qualified proposals. We manage every project on your behalf
        </p>
      </div>
      <div
        class="h-[230] min-w-[379] flex flex-col items-center justify-center"
      >
        <img
          src="../../assets/HowItWorks/payment-method-1-100x100.png"
          alt=""
        />
        <p
          class="text-white text-[20px] font-[300] leading-[20px] text-center py-[10px]"
        >
          Payment Simplified
        </p>
        <p
          class="text-[#acaaaa] text-[15px] font-[200] leading-[20px] text-center mb-[20px]"
        >
          Pay fixed-price, payments go into escrow, pay for work you approve
        </p>
      </div>
    </div>
    <div class="flex items-center justify-center w-full">
      <button
        class="bg-[#30b352] group text-white hover:bg-[#6ce812] transition duration-500 ease-in w-[178px] h-[48px] text-[16px] font-[300] leading-[16px] px-[15px] rounded-[2px]"
      >
        <div class="block transition duration-500 ease-in group-hover:hidden">
          Post A Job
        </div>
        <div class="hidden transition duration-500 ease-in group-hover:block">
          Get Started
        </div>
      </button>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style></style>
