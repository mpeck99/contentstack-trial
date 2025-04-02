<template>
  <Header />
  <client-only>
    <DevTools />
  </client-only>
  <NuxtPage />
  <Footer />
</template>

<script>
import "vue3-json-viewer/dist/index.css";
useHead({
  script: [
    {
      src: "https://www.contentstack.com/sdks/live-preview.js",
      defer: true,
    },
  ],
});
</script>
<style>
#cslp-tooltip {
  display: none !important;
}
</style>
