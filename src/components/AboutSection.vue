<template>
  <div class="flex flex-wrap justify-center ">
    <div class="w-2/3 sm:w-1/2 md:w-5/12 lg:w-2/12 mb-12 hover-grayscale-0">
      <div class="flex items-center relative"> 
        <div class="absolute border-l-2 border-gray-800 h-full right-0 top-0 bottom-0 mx-2"></div>
        <img src="/avatar1.png" class="max-w-full h-auto mx-auto rounded-full grayscale" alt="title image">
      </div>
    </div>
    <div class=" sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
    <div class="flex flex-col items-start max-w-screen-sm md:flex-row sm:mx-auto">
      <div>
        <p class="mb-2 text-xs font-semibold tracking-wide text-gray-800 uppercase">
          New History
        </p>
        <h2 class="mb-4 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
          Cheese on toast tale
        </h2>
        <p class="text-base text-gray-700 md:text-lg">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
        </p>
        <button type="button" class="mt-6 text-blue-700 hover:text-white border border-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800">
          Entre em contato</button>
          <button type="button" class="mt-6 text-blue-700 hover:text-white border border-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800">
          Baixar CV</button>
      </div>
    </div>
  </div>
      </div>
  </template>
  


<style>
.grayscale  {
    filter: grayscale(100%);
}
.hover-grayscale-0:hover .grayscale {
    filter: grayscale(0%);
}
</style>