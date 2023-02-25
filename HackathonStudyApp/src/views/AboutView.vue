<script setup lang="ts">
import AboutApp from '../components/TheWelcome.vue'
</script>
<template>
  <main>
    <AboutApp />
  </main>
</template>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
