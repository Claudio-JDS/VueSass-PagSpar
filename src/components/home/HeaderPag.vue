<script setup lang="ts">
import LogoImg from '@/assets/logo.png'
import HomeImg from '@/assets/home-image.png'


</script>

<template>
  <header>
    <nav>
      <img :src="LogoImg" alt="logo">
      <span class="linha"></span>
      <ul>
        <li><a href="#nosso-espaco">Nosso espaço</a></li>
        <li><a href="#servico">Servicos</a></li>
        <li><a href="#contatos">Contato</a></li>
      </ul>
    </nav>
    <section id="home">

      <div class="textos-home">
        <h1>Boas-vindas ao seu refúgio de <span> paz e bem-estar</span></h1>
        <button class="btn-main">Quero relaxar</button>
      </div>
      <div class="img-home">
        <img :src="HomeImg" alt="Mulher de bruços recebendo massagem nas costas">
      </div>

    </section>
  </header>
</template>

<style scoped>
@import '../../sass/header/index.css' 
</style>