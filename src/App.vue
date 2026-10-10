<template>
  <div class="page">
    <main class="main-content">
      <RouterView />
    </main>

    <footer class="site-footer">
      <p>InZone</p>
      <p>Frivillighetenshus • Mandag 18:00–21:00</p>
    </footer>
  </div>
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<style>
:root {
  --color-yellow: #ffce04;
  --color-orange: #f8bd3c;
  --color-orange-light: #fcefd3;
  --color-green: #036054;
  /* --color-red: #e82052; */
  --color-red: #b0003a;
  --color-page-bg: #ededed;
  --color-bg: var(--color-page-bg);
  --color-footer-bg: #2b2f36;
  --color-text: #1f2937;
  --color-white: #ffffff;
}
</style>

<style scoped>
.page {
  min-height: 100vh;
  background: var(--color-bg);
  color: var(--color-text);
  font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
}

.main-content {
  padding: 1.5rem;
  width: 100%;
}

.site-footer {
  margin-top: 2rem;
  padding: 1rem 1.5rem;
  text-align: center;
  background: var(--color-footer-bg);
  color: var(--color-white);
}

.site-footer p {
  margin: 0.25rem 0;
}
</style>
