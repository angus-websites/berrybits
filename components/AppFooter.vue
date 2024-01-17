<template>
  <footer class="bg-white rounded-lg shadow dark:bg-[#27252D]">
      <div class="w-full max-w-screen-lg mx-auto p-4 md:py-8">
          <div class="flex flex-row justify-between">
              <div><Mark class="h-16" /></div>
              <ButtonsDarkToggle />
          </div>
          <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
          <span class="block text-sm text-gray-500 sm:text-center dark:text-gray-400"><span>© {{ new Date().getFullYear() }}</span> BerryBits. All Rights Reserved.</span>
      </div>
  </footer>
</template>
