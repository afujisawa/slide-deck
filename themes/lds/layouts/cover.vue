<script setup lang="ts">
import DefaultCover from '@slidev/theme-default/layouts/cover.vue'
</script>

<template>
  <DefaultCover v-bind="$attrs">
    <slot />
  </DefaultCover>
</template>
