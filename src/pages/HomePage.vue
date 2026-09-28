<template>
  <section class="main-layout">
    <section class="left-column">
      <HeroSection />

      <section class="cards">
        <MembershipCard />
        <MeetingTimesCard />
        <DonateCard />
        <ContactCard />
      </section>
    </section>

    <section class="right-column">
      <NewsfeedCard />
    </section>
  </section>
</template>

<script setup lang="ts">
import ContactCard from '../components/home/ContactCard.vue'
import DonateCard from '../components/home/DonateCard.vue'
import HeroSection from '../components/home/HeroSection.vue'
import MeetingTimesCard from '../components/home/MeetingTimesCard.vue'
import MembershipCard from '../components/home/MembershipCard.vue'
import NewsfeedCard from '../components/home/NewsfeedCard.vue'
</script>

<style scoped>
.main-layout {
  display: grid;
  gap: 1rem;
}

.left-column {
  display: grid;
  gap: 1.5rem;
}

.cards {
  display: grid;
  gap: 1rem;
}

@media (min-width: 1024px) {
  .main-layout {
    grid-template-columns: minmax(0, 1fr) minmax(0, 540px);
    align-items: start;
  }

  .cards {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
</style>
