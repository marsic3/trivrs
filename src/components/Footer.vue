<script setup lang="ts">
  const date = `${new Date().getFullYear()}`
</script>

<template>
  <div class="h-16 flex py-4 px-4 w-full mb-6 md:mb-0">
    <p class="mx-auto">
      <a href="/" class="text-purple-500">Diligaf</a> {{ date }}
    </p>
  </div>
</template>
