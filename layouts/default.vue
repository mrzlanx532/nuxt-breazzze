<script setup lang="ts">
import Menu from '~/components/Menu.vue'
</script>

<template>
  <div id="app">
    <div class="page">
      <Menu />
      <slot />
    </div>
  </div>
</template>
