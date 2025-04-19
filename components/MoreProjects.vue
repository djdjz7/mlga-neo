<script setup lang="ts">
defineProps<{
  title: String;
  description: String;
}>();
</script>

<template>
  <div>
    <span font-bold text-xl block>
      {{ title }}
    </span>
    <span text-gray block>{{ description }}</span>
  </div>
</template>
