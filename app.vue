<template>
  <div>
    {{ data?.blub }}
    <NuxtWelcome />
  </div>
</template>

<script lang="ts" setup>
const { data } = await useFetch("/api/test");
</script>
