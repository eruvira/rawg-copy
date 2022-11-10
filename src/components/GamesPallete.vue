<script setup>
import { ref } from 'vue'
import GameCard from './GameCard.vue'
</script>

<template>
  <h1 class="head1">All Games</h1>
  <div class="order-display">
    <div class="order"></div>
    <div class="display"></div>
  </div>
  <div class="games-pallete">
      <GameCard/>
      <GameCard/>
      <GameCard/>
      <GameCard/>
      <GameCard/>
      <GameCard/>
      
  </div>
</template>

<style scoped>

</style>
