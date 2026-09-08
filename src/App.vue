<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <component :is="$route.meta.layout || MainLayout">
    <router-view />
  </component>
</template>

<style scoped></style>
