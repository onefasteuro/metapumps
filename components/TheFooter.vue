<style lang="postcss" scoped>
footer {
  background-color: var(--text-yellow);
  @apply py-11 mt-14;
}

</style>

<template>
  <footer class="w-full the-footer">
    <div class="container mx-auto px-8">
      <div class="mp-logo mx-auto mb-8">
        <img src="/footer-logo.png" alt="Metapumps Logo" class="mx-auto" />
      </div>
      <div class="mp-social">
        <ul class="flex items-center justify-center">
          <li class="mx-3">
            <a><img src="/youtube.png" alt="Check us out on Youtube" /></a>
          </li>
          <li class="mx-3">
            <a><img src="/discord.png" alt="Discuss on Discord" /></a>
          </li>
          <li class="mx-3">
            <a><img src="/ig.png" alt="Follow us on Instagram" /></a>
          </li>
          <li class="mx-3">
            <a><img src="/twitter.png" alt="Follow us on Twitter" /></a>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>
