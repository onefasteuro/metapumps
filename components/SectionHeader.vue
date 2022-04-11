<style lang="postcss" scoped>
.section__header h2 {
  color: var(--text-yellow);
  font-style: italic;
  @apply font-extrabold m-0 text-4xl uppercase;
}
.section__header.buy-metapump h2 {
  color: black;
}
</style>

<template functional>
  <div class="section__header" :class="[props.anchor, data.class || '', data.staticClass || '']">
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
