<template>
    <NuxtPage />
</template>

<script setup lang="ts">
definePageMeta({
    layout: 'dashboard',
    middleware: ['auth']
})
</script>