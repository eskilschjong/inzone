<template>
  <article class="card">
    <h2>Støtt oss</h2>
    <p>
      Vil du bidra til aktiviteter og tilbud i InZone Nevromangfold? Du kan
      støtte oss direkte på Spleis.
    </p>
    <a
      class="donate-button"
      href="https://www.spleis.no/org/26761"
      target="_blank"
      rel="noopener noreferrer"
    >
      <HandHeart :size="18" aria-hidden="true" />
      Doner på Spleis
    </a>
  </article>
</template>

<script setup lang="ts">
import { HandHeart } from '@lucide/vue'
</script>

<style scoped>
.card {
  background: var(--color-orange);
  color: var(--color-text);
  padding: 1.25rem;
  border-radius: 0.75rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.card h2 {
  margin-top: 0;
  color: var(--color-text);
  font-weight: 800;
}

.card p {
  margin: 0 0 1rem;
}

.donate-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  width: fit-content;
  min-width: 12rem;
  margin: 0 auto;
  text-align: center;
  background: var(--color-yellow);
  border: 2px solid #000000;
  color: #000000;
  text-decoration: none;
  font-weight: 600;
  padding: 0.7rem 1.25rem;
  border-radius: 9999px;
  transition: background-color 0.2s ease, box-shadow 0.2s ease, transform 0.2s ease;
}

.donate-button:hover {
  background: #ffe25a;
  transform: translateY(-1px);
}
</style>
