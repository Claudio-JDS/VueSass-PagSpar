<script setup lang="ts">
import EspacoImg1 from '@/assets/espaco-1.png'
import EspacoImg2 from '@/assets/espaco-2.png'
import EspacoImg3 from '@/assets/espaco-3.png'
import SeparadorDireitaImg from '@/assets/separador-direita.svg'
import SeparadorEsquerdoImg from '@/assets/separador-esquerda.svg'

</script>

<template>
  <section id="nosso-espaco">
    <div class="detalhes">
      <div class="imgs-espaco">
        <img class="img-espaco" :src="EspacoImg1"
          alt="Espaço iluminado pelo sol com design futurista composto por piscina e plantas">
      </div>
      <div class="espaco-textos">
        <h2 class="titulo">Tecnologia e natureza potencializando seu relaxamento</h2>
        <p class="infos">Oferecemos equipamentos de ponta, produtos certificados e uma equipe de
          profissionais ultra qualificados para dissipar seu estresse e ajudar você na busca por
          equilíbrio e tranquilidade.</p>
        <img class="separador" :src="SeparadorDireitaImg" alt="separador de seções">
      </div>
    </div>
    <div class="detalhes">
      <div class="imgs-espaco">
        <img class="img-espaco" :src="EspacoImg2" alt="Mulher sentada numa banheira com uma taça na mão">
        <img class="img-espaco" :src="EspacoImg3" alt="Espaço com uma piscina e um sofá ao fundo">
      </div>
      <div class="espaco-textos">
        <h2 class="titulo">Elevando seu bem-estar a um novo patamar</h2>
        <p class="infos">No Calmaria Spa cada visita é uma jornada revigorante para mais serenidade e
          disposição! Independente da sua rotina, vamos ajudar você a encontrar seu paraíso
          particular.</p>
        <img class="separador" :src="SeparadorEsquerdoImg" alt="separador de seções">
      </div>
    </div>
  </section>
</template>

<style scoped>
@import '../../sass/home/home.css'
</style>