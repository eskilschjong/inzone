<template>
  <article class="card">
    <h2>Møtetider</h2>
    <p>
      Vi møtes hver mandag på Frivillighetenshus, fra 18:00 til 21:00. Husk at
      dette er medlemskvelder og at vi allerede kanskje har planer for kvelden.
      Du er hjertelig velkommen til å besøke eller komme å se hva vi gjør
      uansett.
    </p>
    <p>
      Vi skal snart holde en åpen kveld igjen, der hvor alle er velkomne og vi
      vil presentere informasjon angående oss, organisasjonen og planene vi har
      framover.
    </p>
  </article>
</template>

<style scoped>
.card {
  background: var(--color-green);
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
</style>
