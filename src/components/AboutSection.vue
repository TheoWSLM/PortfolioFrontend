<script setup>
const base = import.meta.env.BASE_URL;
</script>

<template>
  <section id="sobre" class="about-section section-anchor section-pad">
    <div class="shell about-grid">
      <div class="about-visual">
        <div class="illustration-frame">
          <img
            :src="`${base}avatar1.png`"
            alt="Ilustração original do portfólio: computador com símbolo de código"
            loading="lazy"
          /><span class="illustration-marker">&lt; / &gt;</span>
        </div>
        <span class="visual-caption"
          >CURIOSIDADE TÉCNICA DESDE O PRIMEIRO PROJETO ↗</span
        >
      </div>
      <div class="about-copy">
        <div class="section-label">
          <span>01 / SOBRE</span><span class="label-rule"></span>
        </div>
        <h2>Entre o modelo e o produto, existe <em>engenharia.</em></h2>
        <p>
          Sou AI Engineer e desenvolvedor de software com mais de 6 anos de
          experiência. Hoje trabalho na construção de agentes conversacionais,
          sistemas RAG e serviços de IA integrados a produtos reais.
        </p>
        <p>
          Minha atuação une arquitetura de backend, interfaces web e operação em
          cloud. Gosto de sistemas úteis para as pessoas e sustentáveis para
          quem precisa medir, manter e evoluir.
        </p>
        <div class="about-facts">
          <div><strong>6+ anos</strong><span>desenvolvendo software</span></div>
          <div>
            <strong>End-to-end</strong><span>da arquitetura à produção</span>
          </div>
          <div>
            <strong>PT / EN</strong><span>comunicação profissional</span>
          </div>
        </div>
        <a class="text-link" href="mailto:theoweber1@gmail.com"
          >Vamos criar algo juntos <span aria-hidden="true">↗</span></a
        >
      </div>
    </div>
  </section>
</template>
