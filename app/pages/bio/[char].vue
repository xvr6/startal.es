<script lang="ts" setup>
const route = useRoute();
const who = route.params.char?.toString();

console.log(who);
</script>

<template>
  <UContainer class="mt-4">
    <p>{{ who }}</p>
  </UContainer>
  <!-- use new layout tupe for other character pages instead of this stupid dynamic component thing  -->
</template>

<style></style>
