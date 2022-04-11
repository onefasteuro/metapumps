<style lang="postcss" scoped>
footer {
  background-color: var(--text-yellow);
  @apply py-11 mt-14;
}

.mp-social li img {
  width: 30px;
  height: auto;
}

</style>

<template>
  <footer class="w-full the-footer">
    <div class="container mx-auto">
      <div class="mp-logo">

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
