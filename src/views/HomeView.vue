<script setup>
import AboutSection from "@/components/AboutSection.vue";
import Banner from "@/components/Banner.vue";
import ExperienceSection from "@/components/ExperienceSection.vue";
import TecnologySection from "@/components/TecnologySection.vue";

const evaluationSteps = [
  {
    index: "01",
    name: "Definir",
    description: "Casos reais, critérios de resposta e limites de segurança.",
  },
  {
    index: "02",
    name: "Testar",
    description: "Qualidade, cobertura e recuperação de contexto.",
  },
  {
    index: "03",
    name: "Observar",
    description: "Latência, custo, falhas e comportamento em produção.",
  },
  {
    index: "04",
    name: "Evoluir",
    description: "Ajustar prompts, ferramentas e fluxos com evidência.",
  },
];
</script>

<template>
  <main>
    <Banner /><AboutSection />
    <section
      id="especialidades"
      class="expertise-section section-anchor section-pad"
    >
      <div class="shell">
        <div class="section-label">
          <span>02 / O QUE EU FAÇO</span><span class="label-rule"></span>
        </div>
        <div class="section-heading-row">
          <h2>IA aplicada.<br /><em>Resultado observável.</em></h2>
          <p>
            Um agente precisa responder bem, usar as ferramentas certas e ser
            acompanhado depois da entrega.
          </p>
        </div>
        <div class="expertise-grid">
          <article class="expertise-card expertise-card-primary">
            <div class="card-topline">
              <span>01 / AI ENGINEERING</span><span>✳</span>
            </div>
            <div class="agent-graphic">
              <span class="agent-ring agent-ring-one"></span
              ><span class="agent-ring agent-ring-two"></span
              ><span class="agent-core">AI</span
              ><span class="agent-label label-context">CONTEXT</span
              ><span class="agent-label label-tools">TOOLS</span
              ><span class="agent-label label-memory">STATE</span>
            </div>
            <div>
              <h3>Agentes que sabem agir.</h3>
              <p>
                Orquestro fluxos com LangGraph e LangChain, combinando estado,
                roteamento dinâmico, tool calling e MCP para resolver tarefas
                com controle.
              </p>
            </div>
          </article>
          <article class="expertise-card expertise-card-secondary">
            <div class="card-topline">
              <span>02 / RETRIEVAL</span><span>↗</span>
            </div>
            <div class="retrieval-graphic">
              <div><i></i><i></i><i></i></div>
              <span>DOCS</span><span class="retrieval-arrow">→</span
              ><span class="retrieval-search">⌕</span
              ><span class="retrieval-arrow">→</span><span>ANSWER</span>
            </div>
            <div>
              <h3>Conhecimento no contexto.</h3>
              <p>
                Construo RAG com busca vetorial e Azure AI Search para respostas
                apoiadas nas fontes certas, no momento certo.
              </p>
            </div>
          </article>
          <article class="expertise-card expertise-card-tertiary">
            <div class="card-topline">
              <span>03 / PRODUCT ENGINEERING</span><span>↗</span>
            </div>
            <div class="code-graphic">
              <div class="code-dots"><i></i><i></i><i></i></div>
              <code
                ><span>POST</span> /agent/run<br /><small
                  >→ stream(response)</small
                ><br /><small>→ trace + evaluate</small></code
              >
            </div>
            <div>
              <h3>Do protótipo à produção.</h3>
              <p>
                Entrego APIs em FastAPI, interfaces em React/Vue e sistemas
                distribuídos em cloud, com testes, CI/CD e observabilidade.
              </p>
            </div>
          </article>
        </div>
        <div class="evaluation-panel">
          <div class="evaluation-intro">
            <div class="mini-label">
              <span class="status-dot"></span> EVALUATION / QUALITY LOOP
            </div>
            <h3>Qualidade de IA<br />se <em>mede.</em></h3>
            <p>
              Combino avaliações de LLM, guardrails e observabilidade para
              melhorar respostas com critérios claros.
            </p>
            <div class="eval-signals">
              <span>✓ Relevância</span><span>✓ Fundamentação</span
              ><span>✓ Segurança</span><span>✓ Latência & custo</span>
            </div>
          </div>
          <div class="evaluation-flow">
            <div
              v-for="step in evaluationSteps"
              :key="step.index"
              class="evaluation-step"
            >
              <span class="step-index">{{ step.index }}</span>
              <div>
                <strong>{{ step.name }}</strong>
                <p>{{ step.description }}</p>
              </div>
              <span class="step-arrow" aria-hidden="true">↘</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <ExperienceSection /><TecnologySection />
  </main>
</template>
