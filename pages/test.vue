<template>
  <div>
    <p>Current route: {{ route.path }}</p>
  </div>
</template>

<script setup lang="ts">
  const route = useRoute()
</script>
