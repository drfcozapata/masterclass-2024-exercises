<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
//
</script>

<template>
  <main>
    <h1>Projects View</h1>
    <RouterLink to="/"> Home </RouterLink>
    <RouterLink :to="{ name: '/projects/[id]', params: { id: 1 } }">
      Project 1
    </RouterLink>
  </main>
</template>
