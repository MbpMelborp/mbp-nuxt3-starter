<script setup >
definePageMeta({})
useHead({
  title: 'Nuxt3 Eslint',
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
  @apply w-full flex;
  .port {
    @apply md:w-1/2 w-full;
  }
  .form {
    @apply md:w-1/2 w-full;
  }
}
</style>






