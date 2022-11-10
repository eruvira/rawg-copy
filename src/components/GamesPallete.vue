<script setup>
import { ref } from "vue";
import GameCard from "./GameCard.vue";
import DropDown from "./DropDown.vue";
</script>

<template>
  <h1 class="head1">All Games</h1>
  <div class="order-display">
    <div class="order">
      <p>Order by:</p>
      <DropDown />
      <DropDown />
      <DropDown />
    </div>
    <div class="display">
      <p>Display options:</p>
      <div class="select-options">
        <button class="select-options__item option__colums active"></button>
        <button class="select-options__item option__list"></button>
      </div>
    </div>
  </div>
  <div class="games-pallete">
    <GameCard />
    <GameCard />
    <GameCard />
    <GameCard />
    <GameCard />
    <GameCard />
  </div>
</template>

<style scoped>
@import "../assets/styles/games.css";
</style>
