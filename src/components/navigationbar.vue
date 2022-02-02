<template>
<header class="body-font bg-blue-500">
  <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <a class="flex title-font font-medium items-center text-white mb-4 md:mb-0">
      
      <span class="ml-3 text-xl cursor-pointer">Logo</span>
    </a>
    <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center text-white">
      <a class="mr-5 hover:text-yellow-500 font-bold cursor-pointer">Home</a>
      <a class="mr-5 hover:text-yellow-500 font-bold cursor-pointer">About</a>
      <a class="mr-5 hover:text-yellow-500 font-bold cursor-pointer">Services</a>
      <a class="mr-5 hover:text-yellow-500 font-bold cursor-pointer">testimonial</a>
      <a class="mr-5 hover:text-yellow-500 font-bold cursor-pointer">Contact Us</a>
    </nav>
    <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-yellow-500 rounded text-base mt-4 md:mt-0">Button
      <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
        <path d="M5 12h14M12 5l7 7-7 7"></path>
      </svg>
    </button>
  </div>
</header>
</template>
<script>
export default {
    name: "navigationbar"
}
</script>