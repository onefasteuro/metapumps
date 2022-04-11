<style lang="postcss" scoped>
.roadmap__body {
  @apply mt-4;
  line-height: 1.5;
}
</style>

<template functional>
  <div class="roadmap__body">
    <p class="m-0"><slot /></p>
  </div>
</template>

<script>
export default {
  name: 'RoadmapBody',
}
</script>
