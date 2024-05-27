<script setup lang="ts">
import MandalaEsquerdaImg from '@/assets/mandala-esquerda.png'
import MandalaDireitaImg from '@/assets/mandala-direita.png'
import ContatoImg1 from '@/assets/contato-img-1.png'
import ContatoImg2 from '@/assets/contato-img-2.png'
import ContatoImg3 from '@/assets/contato-img-3.png'


</script>

<template>
  <section id="desconto">
    <img :src="MandalaEsquerdaImg" alt="Mandala lado esquerdo">
    <div class="desconto-form">
      <h4>Inscreva-se para ganhar descontos!</h4>
      <p>Cadastre seu email para receber descontos e novidades sobre o espaço e nossos serviços.</p>
      <div class="input-btn">
        <input type="email">
        <button type="submit">Inscrever</button>
      </div>
    </div>
    <img :src="MandalaDireitaImg" alt="Mandala lado direito">
  </section>
  <section id="contatos">
    <div class="contatos-imgs">
      <img :src="ContatoImg1" alt="Homem deitado em banheira">
      <img :src="ContatoImg2" alt="Mulher olhando para o horizonte dentro de uma banheira">
      <img :src="ContatoImg3" alt="Livro nas mãos de uma pessoa dentro de uma banheira">
    </div>
    <div class="contatos-form">
      <h4 class="titulo">Entre em contato</h4>
      <p class="infos">Reserve seu horário, tire dúvidas ou proponha sugestões, nosso canal é aberto para
        você!</p>
      <form class="inputs">
        <div class="form-group">
          <label for="nomeContato">Nome</label>
          <input type="text" id="nomeContato" placeholder="Digite nome completo">
        </div>
        <div class="form-group">
          <label for="emailContato">Email</label>
          <input type="email" id="emailContato" placeholder="Digite seu email">
        </div>
        <div class="form-group">
          <label for="telefoneContato">Telefone</label>
          <input type="text" id="telefoneContato" placeholder="(xx) xxxxx-xxxx">
        </div>
        <div class="form-group">
          <label for="mensagemContato">Mensagem</label>
          <textarea type="text" id="mensagemContato" placeholder="Escreva sua mensagem"></textarea>
        </div>
        <button class="btn">Enviar</button>
      </form>
    </div>
  </section>
</template>

<style scoped>
@import '../../sass/form/form.css';
</style>