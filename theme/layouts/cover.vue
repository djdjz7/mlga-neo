<script setup lang="ts">
import CoverCornerBadge from "../components/CoverCornerBadge.vue";
</script>

<template>
  <div class="slidev-layout cover relative">
    <CoverCornerBadge />
    <div class="my-auto w-full z-1">
      <slot />
    </div>
  </div>
</template>
