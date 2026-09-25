<script setup>
import { ref } from 'vue'

const menuOpen = ref(false)
const links = [
  { label: 'Sobre', href: '#sobre' },
  { label: 'Especialidades', href: '#especialidades' },
  { label: 'Experiência', href: '#experiencia' },
  { label: 'Stack', href: '#stack' },
]
</script>

<template>
  <header class="site-header">
    <div class="shell header-inner">
      <a class="brand" href="#inicio" aria-label="Theo Weber, voltar ao início" @click="menuOpen = false">
        <span class="brand-mark">&lt;<span>tw</span>/&gt;</span>
        <span class="brand-name">THEO WEBER<span class="brand-dot">.</span></span>
      </a>
      <button class="menu-toggle" type="button" :aria-expanded="menuOpen" aria-controls="main-navigation" :aria-label="menuOpen ? 'Fechar menu' : 'Abrir menu'" @click="menuOpen = !menuOpen"><span></span><span></span></button>
      <nav id="main-navigation" class="header-nav" :class="{ 'is-open': menuOpen }" aria-label="Navegação principal">
        <a v-for="link in links" :key="link.href" :href="link.href" @click="menuOpen = false">{{ link.label }}</a>
        <a class="nav-contact" href="mailto:theoweber1@gmail.com" @click="menuOpen = false">Vamos conversar <span aria-hidden="true">↗</span></a>
      </nav>
    </div>
  </header>
</template>
