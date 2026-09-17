<script setup lang="ts">
withDefaults(defineProps<{ section?: string; tone?: string; cover?: boolean }>(), {
  section: 'Financing community needs', tone: 'paper', cover: false,
})
</script>

<template>
  <div class="slidev-layout own-frame" :class="[tone, { 'own-cover': cover }]">
    <header class="own-index">{{ section }}</header>
    <main class="own-content"><slot /></main>
    <footer class="own-footer">
      <span>VALLEY OF THE COMMONS <span class="footer-divider">/</span> GOVERNANCE &amp; FUNDING</span>
      <span class="footer-right"><span><a href="https://x.com/microHoffman">@microHoffman</a> | <a href="https://own.casa/">own.casa</a></span><span class="own-page"><SlideCurrentNo /></span></span>
    </footer>
  </div>
</template>
