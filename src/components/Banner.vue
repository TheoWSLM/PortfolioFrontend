<script setup>
const base = import.meta.env.BASE_URL;
</script>

<template>
  <section id="inicio" class="hero section-anchor">
    <div class="hero-glow hero-glow-one"></div>
    <div class="hero-glow hero-glow-two"></div>
    <div class="shell hero-grid">
      <div class="hero-copy">
        <div class="eyebrow">
          <span class="status-dot"></span> AI ENGINEER · FULL STACK · MLOPS
        </div>
        <h1>
          Construo IA que <em>funciona</em> no mundo real<span class="period"
            >.</span
          >
        </h1>
        <p class="hero-description">
          Sou Theo Weber. Transformo modelos de linguagem em produtos
          confiáveis: agentes, RAG e APIs que vão da ideia à produção, com
          atenção à qualidade de cada resposta.
        </p>
        <div class="hero-actions">
          <a class="button button-primary" href="#especialidades"
            >Explore meu trabalho <span aria-hidden="true">↗</span></a
          ><a
            class="button button-quiet"
            :href="`${base}dev-theo-weber.pdf`"
            download="Theo-Weber-Curriculo.pdf"
            >Baixar currículo <span aria-hidden="true">↓</span></a
          >
        </div>
        <div class="hero-meta">
          <span>Python & FastAPI</span><span>LangGraph & LangChain</span
          ><span>LLM Evaluation</span>
        </div>
      </div>
      <div class="hero-art">
        <div class="portrait-spotlight">
          <img
            :src="`${base}theo-portrait.png`"
            alt="Foto de Theo Weber"
            fetchpriority="high"
          />
        </div>
        <div class="hero-orbit hero-orbit-one"></div>
        <div class="hero-orbit hero-orbit-two"></div>
        <div class="floating-chip chip-one">
          <span class="chip-icon">✳</span
          ><span>AI SYSTEMS<br /><strong>BUILT TO SHIP</strong></span>
        </div>
        <div class="floating-chip chip-two">
          <span class="status-dot"></span> PRODUCTION READY
        </div>
        <div class="floating-chip chip-three">
          { Python · LangGraph · FastAPI }
        </div>
      </div>
    </div>
    <div class="shell hero-footer">
      <span>ENGENHARIA DE SOFTWARE + INTELIGÊNCIA ARTIFICIAL</span
      ><a href="#sobre">EXPLORE <span aria-hidden="true">↓</span></a>
    </div>
  </section>
</template>
