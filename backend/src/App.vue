<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <h1 class="flex items-center justify-center m-10 text-center text-2xl text-blue-500 font-bold">Hello Vite + TailwindCSS + Vue3</h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
