<script lang="ts" setup>
const route = useRoute();
const who = route.params.char;

console.log(who);
</script>

<template>
  <UContainer class="mt-4">
    <p>{{ who }}</p>
  </UContainer>
</template>

<style></style>
