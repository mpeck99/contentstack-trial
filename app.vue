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
</script>
<style>
#cslp-tooltip {
  display: none !important;
}
</style>
