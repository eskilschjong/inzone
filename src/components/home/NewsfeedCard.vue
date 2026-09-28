<template>
  <section id="siste-nytt" class="newsfeed-section">
    <h2>Siste nytt</h2>
    <div class="feed-wrapper">
      <iframe
        title="InZone Nevromangfold Facebook feed"
        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61579836890772&tabs=timeline&width=500&height=700&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=false"
        width="500"
        height="700"
        style="border:none;overflow:hidden"
        scrolling="no"
        frameborder="0"
        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
      />
    </div>
  </section>
</template>

<style scoped>
.newsfeed-section {
  background: var(--color-white);
  border-radius: 0.75rem;
  padding: 1.25rem;
}

.newsfeed-section h2 {
  margin: 0;
  color: var(--color-green);
  font-weight: 700;
}

.subtitle {
  margin-top: 0.5rem;
  margin-bottom: 1rem;
}

.feed-wrapper {
  width: 100%;
}

.feed-wrapper iframe {
  display: block;
  width: 100%;
}
</style>
