<style lang="postcss" scoped>
.section__header h2 {
  color: var(--text-yellow);
  font-style: italic;
  @apply font-extrabold m-0 text-4xl uppercase;
}
</style>

<template functional>
  <div class="section__header">
    <a :id="anchor" v-if="props.anchor" />
    <h2>
      <slot />
    </h2>
  </div>
</template>

<script>
export default {
  name: 'SectionHeader',
  props: {
    anchor: {
      type: String,
      default: null
    }
  }
}
</script>
