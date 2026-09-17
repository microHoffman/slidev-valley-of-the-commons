<script setup lang="ts">
defineProps<{ section?: string }>()
</script>
<template><OwnFrame :section="section" cover><slot /></OwnFrame></template>
