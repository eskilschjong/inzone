<template>
  <section id="om-oss" class="hero">
    <div class="hero-brand">
      <img src="/Inzone_logo.png" alt="InZone logo" class="hero-logo" />
      <h1>InZone Nevromangfold</h1>
    </div>

    <p>
      Vi er en frivillig organisasjon for personer over 16 år innen
      nevrodiversitetspekteret.
    </p>
  </section>
</template>

<style scoped>
.hero {
  background: var(--color-white);
  border-left: 8px solid var(--color-yellow);
  padding: 2rem;
  border-radius: 0.75rem;
}

.hero-brand {
  display: flex;
  align-items: center;
  gap: 0.9rem;
  margin-bottom: 0.75rem;
}

.hero-logo {
  width: 3.25rem;
  height: 3.25rem;
  object-fit: contain;
  flex: 0 0 auto;
}

.hero h1 {
  margin: 0;
  color: var(--color-green);
  font-weight: 900;
}

.hero p {
  margin: 0;
  max-width: 60ch;
  font-size: 1.125rem;
  font-weight: 500;
}
</style>
