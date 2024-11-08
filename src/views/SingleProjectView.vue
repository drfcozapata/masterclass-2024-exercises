<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
</script>

<template>
  <main>
    <h1>Single Project View: {{ route.params.id }}</h1>
    <RouterLink :to="{ name: 'home' }"> Home </RouterLink>
    <RouterLink :to="{ name: 'projects' }"> Projects </RouterLink>
  </main>
</template>
