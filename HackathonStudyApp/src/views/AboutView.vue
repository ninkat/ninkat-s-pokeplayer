<script setup lang="ts">
import AboutMe from "../components/AboutApp.vue"
</script>
<template>
  <main>
    <AboutMe/>
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
