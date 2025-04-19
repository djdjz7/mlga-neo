<script setup lang="ts">
import DefaultCornerBadge from "../components/DefaultCornerBadge.vue";
</script>

<template>
  <div class="slidev-layout default relative">
    <DefaultCornerBadge />
    <div class="my-auto w-full z-1">
      <slot />
    </div>
  </div>
</template>
