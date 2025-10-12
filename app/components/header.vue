<template>
  <div>
    <nav class="bg-[#EEF1FF] w-full md:w-[318px] fixed top-0 left-0 h-[70px] md:h-screen flex md:block justify-center md:justify-start items-center z-50">
      <h1 class="p-4 md:p-6 text-[32px] md:text-[40px] leading-[20px] bg-gradient-to-r from-[#463ADD] via-[#FF00FB] text-transparent bg-clip-text font-extrabold animate-pulse">
        TAILWIND
      </h1>
    </nav>

    <div class="flex flex-row justify-between items-center mt-[100px] md:mt-3 mb-5 font-semibold text-[24px] px-4 md:px-0 relative z-40">
      <h1 class="md:ml-[350px] text-left">
        My catalogs
      </h1>
      <button class="flex justify-center items-center gap-2 mr-[5px] bg-[#463ADD] hover:bg-[#FF00FB] text-white font-medium text-[14px] rounded-md px-4 py-2 transition">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
          <path d="M12 8v8M8 12h8" stroke-linecap="round" stroke-linejoin="round" />
        </svg>

        <span>Create catalog</span>
      </button>
    </div>

    <div class="border-b border-gray-300"></div>
  </div>
</template>
