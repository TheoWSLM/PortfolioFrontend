<template>
  <div class=" flex items-center justify-center mb-10 ">
    <div class=" w-8/12 relative border-s mx-auto border-gray-200 dark:border-gray-700 flex-wrap items-center justify-center">
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
          <div class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">Descrição das atividades</div>
          <p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">{{ item.description }}</p>
        </li>
        
      </ol>
      <div class="flex justify-center">
  <button type="button" class="items-center text-green-500 hover:text-white border border-green-500 hover:bg-green-500 focus:ring-4 focus:outline-none focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2 dark:border-blue-500 dark:text-blue-500 dark:hover:text-white dark:hover:bg-blue-500 dark:focus:ring-blue-800">
    Baixar CV
  </button>
</div>
    </div>
    
</div>


  </template>
  

  <script>
export default {
  data() {
    return {
      items: [
        {
          title: "ComplySoft Solutions",
          tag: "Atual",
          description: "Atuo no desenvolvimento Fullstack, utilizando Java, Spring Boot, C#, .NET, Angular, TypeScript e Vue.js conforme a necessidade do projeto. Participei da construção de softwares ERP focados em camadas B2B, B2C e C2B para o mercado de fitoterápicos. Domino MySQL e PostgreSQL na construção de bancos de dados relacionais, realizando manutenção de sistemas legados, implementação de novas funcionalidades e integração de API's externas. Opero em ambientes de nuvem AWS, desenvolvo interfaces no Figma e crio softwares de automação para operações internas. Tudo isso sob a metodologia ágil Kanban, gerenciada pela ferramenta Jira.",

        },
        {
          title: "Projeto de extensão robótica UFPB",
          tag: "Latest",
          description: "Desenvolvimentos de algoritmos em Python eficientes para controle e automação de dispositivos robóticos com utilização de ferramentas como PyRobot, ROS entre outros. Criação de interfaces de programação de especificação e funcionamento utilizando React para monitoramento e controle remoto.",

        },
        {
          title: "Energia empreendimentos LTDA",
          tag: "Latest",
          description: "Realização de medições de resistência de solo, construção de sistema controle e automação industrial, utilização do Power BI para construção de tabelas e documentações de análises, utilização de metodologia ágil.",

        },
      ]
    };
  }
}
</script>