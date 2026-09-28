<template>
  <article id="medlemskap" class="card">
    <h2>Bli medlem</h2>
    <p>
      For å bli medlem sender du fult navn, mobilnummer og foretrukken e-post
      adresse til:
    </p>
    <p><a href="mailto:inzone.no@gmail.com">inzone.no@gmail.com</a></p>
    <p>
      Du må ikke være medlem for å møte opp, men er du ikke medlem får du ikke
      informasjon om aktiviteter eller mulige endringer av planer. Det er ingen
      krav for å møte opp eller være aktiv, du kommer og tar del i det du selv
      vil.
    </p>
  </article>
</template>

<style scoped>
.card {
  background: var(--color-red);
  color: var(--color-white);
  padding: 1.25rem;
  border-radius: 0.75rem;
}

.card h2 {
  margin-top: 0;
  color: var(--color-white);
}

.card p + p {
  margin-top: 0.75rem;
}

.card a {
  color: var(--color-yellow);
  font-weight: 700;
}
</style>
