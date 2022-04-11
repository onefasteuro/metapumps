<template>
  <div class="container mx-auto px-8">
    <div>
      <img src="/banner.jpg" alt="Welcome to the Metagym" />
    </div>
    <section class="section--welcome section">
      <SectionHeader>Welcome to <br />the Metapumps Gym</SectionHeader>
      <SectionBody>
        <div class="md:grid md:grid-cols-2 md:gap-x-14">
          <div>
            <p>MetaPumps by Jay Cutler is excited to announce a project which will bring blockchain utility to bodybuilding and bodybuilding culture to the Metaverse and beyond!  MetaPumps is releasing its first NFT project: a personality-themed collection of 9600 unique NFTs total with 100 Limited Edition Jay Cutler NFTs. The NFTs will drop on the Ethereum blockchain and the OpenSea platform, trusted by millions of users. They will also serve as admission tickets to the MetaGym, the first-ever hybrid global-Metaverse project for fitness enthusiasts. This legendary NFT release collaborates with one of the greatest bodybuilders of all time, the 4-time Mr. Olympia.</p>
          </div>
          <div class="mt-8 md:mt-0">
            <div class="grid grid-cols-2 gap-8">
              <div class="nft-avatar">
                <img src="/nft-1.png" alt="NFT Photo" />
              </div>
              <div class="nft-avatar">
                <img src="/nft-2.png" alt="NFT Photo" />
              </div>
              <div class="nft-avatar">
                <img src="/nft-3.png" alt="NFT Photo" />
              </div>
            </div>
          </div>
        </div>
      </SectionBody>
    </section>
    <section class="section section--buy">
      <div class="buy-a-metapump">
        <div>
          <SectionHeader anchor="buy-metapump" class="text-center">Buy a Metapump</SectionHeader>
          <div class="mt-8 text-center">
            <button>Buy Now</button>
          </div>
        </div>
        <div>
          <img src="/buy-nft.png" alt="Buy Metapump NFT" />
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
    <section class="section">
      <SectionHeader anchor="the-team">The Team</SectionHeader>
      <SectionBody>
        <div class="grid grid-cols-3 gap-8">
          <div class="">
            <CardAvatar title="Jay Cutler"
                        caption="4x Mr. Olympia">
              <template #image>
                <div class="nft-avatar">
                  <img src="/jay-avatar.jpg" alt="Jay Cutler's NFT" />
                </div>
              </template>
            </CardAvatar>
          </div>
          <div class="">
            <CardAvatar class="basis-1/3 grow-0 shrink-0"
                        title="Whitney Reid"
                        caption="4x Mr. Olympia">
              <template #image>
                <div class="nft-avatar">
                  <img src="/whitney-avatar.jpg" alt="Whitney Reid's NFT" />
                </div>
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
