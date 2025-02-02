<script setup lang="ts"></script>
<template>
  <div class="bg-[url('/bgDark.avif')] bg-cover bg-center h-screen">
    <div
      class="min-[1800px]:mx-[clamp(2rem,_25.55vw,_707px)] xl:mx-[clamp(2rem,_15.55vw,_707px)] mx-[clamp(1rem,_5.55vw,_707px)] pt-[128px]"
    >
      <div
        class="text-[clamp(2rem,_5.55vw,_64px)] font-[600] leading-[clamp(2rem,_5.55vw,_64px)] max-sm:text-center max-w-[680px]"
      >
        The documentation you want, effortlessly
      </div>
      <div
        class="pt-[24px] text-[18px] text-[#ffffffb3] leading-[27px] max-w-[620px] max-sm:text-center"
      >
        Meet the modern standard for documentation. Beautiful out of the box,
        easy to maintain, and built to convert users.
      </div>
      <div class="mt-[32px] pb-[80px] flex max-sm:flex-col gap-2 items-center">
        <RouterLink
          to="/"
          class="bg-white text-black font-[600] rounded-[10px] text-center py-[11px] px-[20px] max-sm:w-full"
          >Get started</RouterLink
        >
        <RouterLink
          to="/"
          class="border border-[#ffffff26] font-[600] rounded-[10px] text-center py-[11px] px-[20px] max-sm:w-full"
        >
          Get a demo</RouterLink
        >
      </div>
    </div>
  </div>
</template>
