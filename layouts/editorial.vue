<script setup lang="ts">
defineProps<{ section?: string }>()
</script>
<template><OwnFrame :section="section"><slot /></OwnFrame></template>
