<template>
  <div>
    <main>
      <!-- Le contenu des pages s'affichera ici -->
      <NuxtPage />

    </main>
  </div>
  <Analytics />
  <SpeedInsights />
</template>

<script setup>
// Aucun script spécifique ici
import { Analytics } from '@vercel/analytics/vue';
import { SpeedInsights } from '@vercel/speed-insights/vue';
</script>

<style scoped>
/* Ton style global ici */
main {
  text-align: center;
  padding: 2rem;
  background-color: #000000;
  color: #f5f5f5;
  font-family: 'Times New Roman', serif;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
