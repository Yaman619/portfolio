<template>
  <div class="flex flex-col min-h-screen bg-secondary-dark">
    <Navigation />
    <RouterView />
    <justified-grid />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router';
import Navigation from './components/navigation.vue';
import {justified-grid} from './components/grid.vue';
</script>

<style lang="scss" scoped>

</style>