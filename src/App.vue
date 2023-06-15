<script setup lang="ts">
import GameHeader from './components/GameHeader.vue';
import GameFigure from './components/GameFigure.vue';
import GameWrongLetters from './components/GameWrongLetters.vue';
import GameWord from './components/GameWord.vue';
import GamePopup from './components/GamePopup.vue';
</script>

<template>
  <GameHeader />
  <div class="game-container">
    <GameFigure />
    <GameWrongLetters />
    <GameWord />
  </div>

  <GamePopup />

  <!-- Notification -->
  <div class="notification-container show">
    <p>Вы уже вводили этот символ</p>
  </div>
</template>