<template>
  <div>
    <pre :style="{ color: checked ? 'green' : 'red' }">{{ { checked } }}</pre>
  </div>
</template>

<script lang="ts" setup>
defineProps<{
  checked?: boolean
}>()
</script>