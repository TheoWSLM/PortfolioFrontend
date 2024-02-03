<template>


    <div class="relative border-s mx-auto border-gray-200 dark:border-gray-700 flex-wrap items-center justify-center h-screen">
      <ol class="border-gray-200 dark:border-gray-700 gap-8 md:gap-20">
        <li v-for="(item, index) in items" :key="index" class="mb-10 ms-6 fill-indigo-300">
            <span class="flex items-center absolute -start-3 justify-center w-6 h-6 bg-indigo-200 rounded-full ring-8 ring-white dark:ring-gray-900 dark:bg-blue-900">
              <svg class="w-2.5 h-2.5  text-green-500 dark:text-blue-300 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                <path d="M20 4a2 2 0 0 0-2-2h-2V1a1 1 0 0 0-2 0v1h-3V1a1 1 0 0 0-2 0v1H6V1a1 1 0 0 0-2 0v1H2a2 2 0 0 0-2 2v2h20V4ZM0 18a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8H0v10Zm5-8h10a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z"/>
              </svg>
            </span>
            <h3 class="flex items-center text-lg font-medium uppercase text-gray-500 dark:text-white">{{ item.title }} 
                <span v-if="index === 0" class="bg-indigo-200 text-green-500 text-sm font-medium me-2 px-2.5 py-0.5 rounded dark:bg-blue-900 dark:text-blue-300 ms-3">
                  {{ item.tag }}</span></h3>
          <time class="block mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ item.date }}</time>
          <p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">{{ item.description }}</p>
        </li>
      </ol>
    </div>
  </template>
  

  <script>
export default {
  data() {
    return {
      items: [
        {
          title: "Flowbite Application UI v2.0.0",
          tag: "Atual",
          date: "Released on January 13th, 2022",
          description: "Get access to over 20+ pages including a dashboard layout, charts, kanban board, calendar, and pre-order E-commerce & Marketing pages.",
          link: "#"
        },
        {
          title: "Flowbite Application UI v2.0.0",
          tag: "Latest",
          date: "Released on January 13th, 2022",
          description: "Get access to over 20+ pages including a dashboard layout, charts, kanban board, calendar, and pre-order E-commerce & Marketing pages.",
          link: "#"
        },
        {
          title: "Flowbite Application UI v2.0.0",
          tag: "Latest",
          date: "Released on January 13th, 2022",
          description: "Get access to over 20+ pages including a dashboard layout, charts, kanban board, calendar, and pre-order E-commerce & Marketing pages.",
          link: "#"
        },
        // Adicione mais objetos conforme necessário
      ]
    };
  }
}
</script>