<script setup>
const groups = [
  {
    number: "01",
    title: "IA & Agentes",
    caption: "Da orquestração à resposta",
    skills: [
      "LangGraph",
      "LangChain",
      "AI Agents",
      "RAG",
      "Tool Calling",
      "MCP",
      "AWS Bedrock",
      "Azure OpenAI",
    ],
  },
  {
    number: "02",
    title: "Backend & Dados",
    caption: "Bases sólidas para escalar",
    skills: [
      "Python",
      "FastAPI",
      "REST APIs",
      "PostgreSQL",
      "MongoDB",
      "Redis",
      "Celery",
      "SQS",
    ],
  },
  {
    number: "03",
    title: "Produto & Cloud",
    caption: "Entrega de ponta a ponta",
    skills: [
      "TypeScript",
      "React",
      "Vue.js",
      "Docker",
      "Kubernetes",
      "AWS / ECS",
      "CI/CD",
      "Pytest",
    ],
  },
];
</script>

<template>
  <section id="stack" class="stack-section section-anchor section-pad">
    <div class="shell">
      <div class="section-label">
        <span>04 / FERRAMENTAS</span><span class="label-rule"></span>
      </div>
      <div class="section-heading-row">
        <h2>Minha caixa de<br /><em>ferramentas.</em></h2>
        <p>
          Escolho a tecnologia pelo problema. Estas são as que uso para
          construir, testar e colocar soluções no ar.
        </p>
      </div>
      <div class="stack-grid">
        <article v-for="group in groups" :key="group.number" class="stack-card">
          <div class="stack-card-top">
            <span>{{ group.number }} / 03</span><span>↗</span>
          </div>
          <h3>{{ group.title }}</h3>
          <p>{{ group.caption }}</p>
          <div class="stack-skills">
            <span v-for="skill in group.skills" :key="skill">{{ skill }}</span>
          </div>
        </article>
      </div>
      <p class="stack-note">
        Também trabalho com observabilidade de LLMs (Datadog, Grafana, New
        Relic), testes com Pytest e fundamentos de arquitetura limpa, DDD e
        SOLID.
      </p>
    </div>
  </section>
</template>
