<script setup lang="ts">
const { data } = await useFetch("/api/hello");
</script>

<template>
  <pre>Data from server: {{ data }}</pre>
</template>
