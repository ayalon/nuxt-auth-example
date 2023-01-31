<template>
  <div class="text-center mt-10">
    <h1 class="text-2xl font-bold">I should be protected</h1>
    <h3>But this seems not to work.</h3>
  </div>
</template>

<script lang="ts" setup>
definePageMeta({ middleware: 'auth' })
</script>

<style scoped>
a {
  @apply text-green-600 underline hover:text-green-500;
}
</style>
