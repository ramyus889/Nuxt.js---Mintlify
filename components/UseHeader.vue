<template>
  <div class="">
    <div class="fixed top-0 left-0 right-0">
      <div
        class="mx-[707px] py-[9px] px-[8px] rounded-2xl backdrop-blur-sm my-[8px]"
      >
        <div class="flex justify-between items-center">
          <div class="px-[8px]">
            <img src="/Logo.svg" width="110px" height="24px" alt="" />
          </div>
          <div class="flex *:text-[#ffffffb3] *:font-[600] *:text-[14px]">
            <RouterLink to="/" class="px-[16px] py-[6px]">Resources</RouterLink>
            <RouterLink to="/" class="px-[16px] py-[6px]"
              >Request Preview</RouterLink
            >
            <RouterLink to="/" class="px-[16px] py-[6px]">Careers</RouterLink>
            <RouterLink to="/" class="px-[16px] py-[6px]">Pricing</RouterLink>
          </div>
          <div class="flex items-center gap-[8px] *:text-[14px] *:font-[600]">
            <RouterLink to="/" class="py-[6px] px-[12px]">Login</RouterLink>
            <RouterLink
              to="/"
              class="border border-[#ffffff26] rounded-[10px] py-[7px] px-[12px]"
              >Get a demo</RouterLink
            >
            <RouterLink
              to="/"
              class="bg-white text-black rounded-[10px] py-[7px] px-[12px]"
              >Sign Up</RouterLink
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
