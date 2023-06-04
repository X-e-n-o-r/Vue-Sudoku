<script setup lang="ts">
</script>

<template>
    <header className="header">
      <h1>
        <span className="header__group-one">Sudoku</span><span className="header__group-two"></span>
      </h1>
      <h2 @click="$emit('newGame')">
        New Game
      </h2>
    </header>  
</template>

<style>

</style>