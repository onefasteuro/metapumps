<style lang="postcss" scoped>
h2 {
  color: var(--text-color);
  @apply font-bold text-2xl mb-2 leading-tight;
  font-style: italic;
}
p {
  color: var(--text-color);
  @apply m-0 text-base;
  font-style: italic;
}
.card-avatar__body {
  @apply mt-6;
}
</style>

<template functional>
  <div class="card-avatar" :class="[data.class || '', data.staticClass || '']">
    <figure>
      <slot name="image" />
    </figure>
    <div class="card-avatar__body">
      <h2>{{ props.title }}</h2>
      <p>{{ props.caption }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardAvatar',
  props: {
    title: {
      type: String
    },
    caption: {
      type: String
    }
  }
}
</script>
