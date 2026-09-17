<script setup lang="ts">
defineProps<{ section?: string }>()
</script>
<template><OwnFrame :section="section" tone="blueprint"><slot /></OwnFrame></template>
