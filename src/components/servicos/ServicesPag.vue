<script setup lang="ts">
import IconMassag from '@/assets/icon-massagem.png'
import SoftStarImg from '@/assets/Soft Star.png'
import IconTratamentos from '@/assets/icon-tratamentos.png'
import IconDiasEspeciais from '@/assets/icon-dias-especiais.png'


</script>

<template>
  <section id="servico">

    <div class="cards">
      <div class="card">
        <img :src="IconMassag" alt="Icone de massagem">
        <h3 class="card-titulo">Massagens</h3>
        <img :src="SoftStarImg" alt="soft star">
        <p class="card-texto">Relaxantes, terapêuticas, desportivas e drenagens. Conte com nossos
          terapeutas especializados para aliviar suas tensões, tratar dores e retenção de líquido
          através
          dessa técnica milenar tão eficiente para o organismo humano.</p>
      </div>
      <div class="card">
        <img :src="IconTratamentos" alt="Icone de tratamento com figura de uma banheira">
        <h3 class="card-titulo">Tratamentos Corporais</h3>
        <img :src="SoftStarImg" alt="soft star">
        <p class="card-texto">Tratamos sua pele com gentileza através de esfoliações corporais suaves,
          hidratações profundas do corpo e do rosto, além de limpeza facial. Você também pode
          desfrutar de
          banhos revigorantes de sais.</p>
      </div>
      <div class="card">
        <img :src="IconDiasEspeciais" alt="Icone de Dias especiais com figura de produtos">
        <h3 class="card-titulo">Dias especiais</h3>
        <img :src="SoftStarImg" alt="soft star">
        <p class="card-texto">Pacotes cuidadosamente elaborados, desde o "Dia Revitalizante" com
          massagens e tratamentos faciais, até o "Dia Serenidade" com banhos terapêuticos e meditação.
          Mime-se com momentos de refúgio de tranquilidade.</p>
      </div>
    </div>

  </section>
</template>

<style scoped></style>