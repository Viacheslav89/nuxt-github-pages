<template>
  <div>
    <p>{{ error.statusCode }}</p>
    <p>Oooops.</p>
    <p>{{ error.message }}</p>
  </div>
  <button @click="handleClearError">Go Home...</button>
</template>

<script setup lang="ts">
  defineProps(["error"]);

const handleClearError = () => clearError({redirect: '/'});

</script>

<style scoped lang="scss"></style>
