<style lang="postcss" scoped>
.section__body {
  @apply mt-11;
  @apply pl-11;
}
</style>

<template functional>
  <div class="section__body">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'SectionBody',
}
</script>
