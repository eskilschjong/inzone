<template>
  <article id="kontakt" class="card">
    <h2>Kontakt</h2>
    <p>
      Hvis du syntes det er litt skummelt å møte opp alene eller trenger å bli
      litt trygg på oss først kan vi ordne samtaler eller møte på forhånd,
      kjøring og henting, eller å møtes nede ved inngangen.
    </p>
    <p>
      Har du flere spørsmål kan du sende oss en melding på Facebook eller
      Messenger, eller kontakte oss på:
    </p>
    <div class="button-group">
      <a
        class="contact-button"
        href="https://www.instagram.com/inzonevromangfold/"
        target="_blank"
        rel="noopener noreferrer"
      >
        Instagram
      </a>
      <a class="contact-button" href="mailto:inzone.no@gmail.com">E-post</a>
    </div>
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

.button-group {
  margin-top: 1rem;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.contact-button {
  display: inline-block;
  min-width: 10.5rem;
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

.contact-button:hover {
  background: #ffe25a;
  transform: translateY(-1px);
}
</style>
