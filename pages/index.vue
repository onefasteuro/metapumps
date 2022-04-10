<template>
  <div class="container mx-auto">
    <div>
      <img src="~/assets/banner.jpg" alt="Welcome to the Metagym" />
    </div>
    <section class="section--welcome section">
      <div class="container mx-auto">

      </div>
    </section>
    <section class="section section--buy">
      <div class="container mx-auto">
        <div class="buy-a-metapump">
            <div>
              Buy A Metapump
            </div>
          <div>

          </div>
        </div>
      </div>
    </section>
    <section class="section section--roadmap">
      <a id="roadmap"></a>
      <SectionHeader anchor="roadmap">Roadmap</SectionHeader>
      <SectionBody>
        aa
      </SectionBody>
    </section>
    <section>
      <SectionHeader anchor="the-team">The Team</SectionHeader>
      <SectionBody>
        <div class="grid grid-cols-3 gap-8">
          <div class="">
            <CardAvatar title="Jay Cutler"
                        caption="4x Mr. Olympia">
              <template #image>
                <img src="~/assets/jay-avatar.jpg" />
              </template>
            </CardAvatar>
          </div>
          <div class="">
            <CardAvatar class="basis-1/3 grow-0 shrink-0"
                        title="Whitney Reid"
                        caption="4x Mr. Olympia">
              <template #image>
                <img src="~/assets/whitney-avatar.jpg" />
              </template>
            </CardAvatar>
          </div>
        </div>
      </SectionBody>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
