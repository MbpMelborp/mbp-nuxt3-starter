<script setup>
import { onMounted, ref } from 'vue'
console.log('INIT PAGE ')
definePageMeta({})
useHead({
  title: 'Nuxt3 Eslint',
})
onMounted(() => {
  console.log('MOUNTED PAGE ')
})
</script>

<template>
  <div class="wrapper">
    <div class="port">imagen</div>
    <div class="form">form</div>
  </div>
</template>

<style lang="postcss" scoped>
.wrapper {
  @apply flex w-full;
  .port {
    @apply w-full md:w-1/2;
  }
  .form {
    @apply w-full md:w-1/2;
  }
}
</style>
