<style lang="postcss" scoped>
.the-header > div {
  @apply flex;
}
.the-header {
  @apply py-12;
}
.the-header > div {
  @apply justify-center flex flex-wrap flex-row md:justify-between items-end;
}

.the-header__logo {
  max-width: 140px;
}

.mp-social li img {
  width: 20px;
}

.the-header__nav nav {
  @apply flex flex-wrap flex-row;
}
.the-header__nav {
  @apply flex flex-wrap flex-row items-center justify-center;
}

.the-header__nav nav > div {
  @apply mx-3;
}
.the-header__nav a {
  @apply uppercase text-sm cursor-pointer;
}
.the-header__nav a:hover {
  color: var(--text-yellow);
}


</style>

<template>
  <header class="w-full the-header">
    <div class="container mx-auto px-8">
      <div class="the-header__logo mb-6 md:mb-0">
        <img src="/header-logo.png" alt="Metapumps Logo" />
      </div>
      <div class="the-header__nav">
        <nav>
          <div>
            <a>Buy a MP</a>
          </div>
          <div>
            <a>Roadmap</a>
          </div>
          <div>
            <a>Team</a>
          </div>
          <div>
            <a>Gallery</a>
          </div>
        </nav>
        <div class="mp-social md:ml-8 mt-4 md:mt-0">
          <ul class="flex items-center justify-center">
            <li class="mx-3">
              <a><img src="/youtube-white.png" alt="Check us out on Youtube" /></a>
            </li>
            <li class="mx-3">
              <a><img src="/discord-white.png" alt="Discuss on Discord" /></a>
            </li>
            <li class="mx-3">
              <a><img src="/ig-white.png" alt="Follow us on Instagram" /></a>
            </li>
            <li class="mx-3">
              <a><img src="/twitter-white.png" alt="Follow us on Twitter" /></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>
