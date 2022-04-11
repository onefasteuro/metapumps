<style lang="postcss" scoped>
.roadmap__header h3 {
  color: white;
  @apply font-bold text-base leading-tight;
}
.roadmap__header {
  @apply mb-6;
}
</style>

<template functional>
  <div class="roadmap__header">
    <h3><slot /></h3>
  </div>
</template>

<script>
export default {
  name: 'RoadmapHeader',
}
</script>
