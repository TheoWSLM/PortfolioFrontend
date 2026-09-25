<script setup>
const base = import.meta.env.BASE_URL;
</script>

<template>
  <footer id="contato" class="site-footer section-anchor">
    <div class="shell">
      <div class="footer-top">
        <div class="section-label">
          <span>05 / CONTATO</span><span class="label-rule"></span>
        </div>
        <span>IDEIAS BOAS COMEÇAM COM UMA CONVERSA.</span>
      </div>
      <h2>Vamos construir<br /><em>algo relevante?</em></h2>
      <a class="footer-email" href="mailto:theoweber1@gmail.com"
        >theoweber1@gmail.com <span aria-hidden="true">↗</span></a
      >
      <div class="footer-bottom">
        <span>© {{ new Date().getFullYear() }} THEO WEBER</span>
        <div>
          <a
            href="https://github.com/TheoWSLM"
            target="_blank"
            rel="noopener noreferrer"
            >GITHUB ↗</a
          ><a
            href="https://www.linkedin.com/in/theo-weber-9b7b09231/"
            target="_blank"
            rel="noopener noreferrer"
            >LINKEDIN ↗</a
          ><a
            href="https://wa.me/5581994249752"
            target="_blank"
            rel="noopener noreferrer"
            >WHATSAPP ↗</a
          ><a
            :href="`${base}dev-theo-weber.pdf`"
            download="Theo-Weber-Curriculo.pdf"
            >CURRÍCULO ↓</a
          >
        </div>
        <a href="#inicio">VOLTAR AO TOPO ↑</a>
      </div>
    </div>
  </footer>
</template>
