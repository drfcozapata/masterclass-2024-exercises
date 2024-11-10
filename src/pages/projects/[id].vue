<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
</script>

<template>
  <main>
    <h1>Single Project View: {{ route.params.id }}</h1>
    <RouterLink to="/"> Home </RouterLink>
    <RouterLink to="/projects"> Projects </RouterLink>
  </main>
</template>
