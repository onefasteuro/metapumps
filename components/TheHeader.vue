<style lang="postcss" scoped>
.the-header > div {
  @apply flex;
}
.the-header {
  @apply py-12;
}
</style>

<template>
  <header class="w-full the-header">
    <div class="container mx-auto">
      <div class="the-header__logo">
      </div>
      <div class="the-header__nav">
        <ul>
          <li>
            <a>Buy a MP</a>
            <a>Roadmap</a>
            <a>Team</a>
            <a>Gallery</a>
            <a>Members</a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>
