<template>
  <header class="site-header">
    <div class="brand">
      <img src="/Inzone_logo.png" alt="InZone logo" class="brand-logo" />
      <span>InZone Nevromangfold</span>
    </div>

    <nav class="nav">
      <RouterLink to="/">Home</RouterLink>
      <a href="#siste-nytt">Siste nytt</a>
    </nav>
  </header>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<style scoped>
.site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 1.5rem;
  background: var(--color-green);
  color: var(--color-white);
}

.brand {
  display: flex;
  align-items: center;
  gap: 0.6rem;
  font-size: 1.4rem;
  font-weight: 700;
}

.brand-logo {
  width: 3rem;
  height: 3rem;
  object-fit: contain;
}

.nav {
  display: flex;
  gap: 1rem;
}

.nav a {
  color: var(--color-white);
  text-decoration: none;
  font-weight: 600;
}

</style>
