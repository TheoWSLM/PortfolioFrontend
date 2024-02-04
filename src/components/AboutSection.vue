<template>
  <div class="flex flex-wrap justify-center mb-24 ">
    <div class="w-2/3 sm:w-1/2 md:w-5/12 lg:w-4/12 mb-12 hover-grayscale-0">
      <div class="flex items-center relative"> 
        <div class="absolute border-l-2 border-gray-300 h-3/4 right-0 top-0 bottom-0 mx-2"></div>
        <img src="/avatar1.png" class=" w-8/12 h-auto mx-auto" alt="title image">
      </div>
    </div>
    <div class=" sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
    <div class="flex flex-col items-start max-w-screen-sm md:flex-row sm:mx-auto">
      <div>
        <h2 class="mb-4 uppercase text-3xl tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
          Sobre mim
        </h2>
        <p class="text-base text-justify text-gray-500 md:text-base">
          Aos 23 anos, no último ano de Engenharia Elétrica na UFPB e 
          avançando no curso de Análise e Desenvolvimento de Sistemas, trago
          uma bagagem de três anos como desenvolvedor Full Stack, com 
          projetos diversificados que abrangem desde a área de comércio e 
          varejo até administração pública. Minha motivação vai além do 
          desenvolvimento de soluções; busco oportunidades para fazer a
          diferença e impactar positivamente o mundo. 
          <p class="text-base text-justify mt-4 text-gray-500 md:text-base">  Estou em busca de
          desafios que me permitam expandir meus conhecimentos, edificando
          minha carreira profisional, contribuindo de forma inovadora para
          equipes e projetos, me alinhando aos valores e propósitos que
          considero essenciais.</p>
        </p>
        <button type="button" class="mt-6 text-green-500 hover:text-white border border-green-500 hover:bg-green-500 focus:ring-4 focus:outline-none focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800">
          Entre em contato</button>
          <button type="button" class="mt-6 text-green-500 hover:text-white border border-green-500 hover:bg-green-500 focus:ring-4 focus:outline-none focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800">
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