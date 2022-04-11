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
            <div class="grid grid-cols-2 gap-11">
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
          <SectionHeader anchor="buy-metapump" class="text-center">Buy<br />a<br />Metapump</SectionHeader>
          <div class="mt-8 text-center">
            <button>Buy Now</button>
          </div>
        </div>
        <div class="mt-8 md:mt-0">
          <img src="/buy-nft.png" alt="Buy Metapump NFT" class="mx-auto" />
        </div>
      </div>
    </section>
    <section class="section section--roadmap">
      <a id="roadmap"></a>
      <SectionHeader anchor="roadmap">Roadmap</SectionHeader>
      <SectionBody>
        <div class="md:grid md:grid-cols-2 md:gap-11">
          <div class="roadmap">
            <RoadmapHeader>Q1 2022</RoadmapHeader>
            <RoadmapBody>
              📆 - Launch social media channels - Twitter and Instagram to begin building initial support and hype for the project, first attracting crypto / NFT buyers, eventually blending in traditional fitness to these channels.
            </RoadmapBody>
            <RoadmapBody>
              📆 - Website to show off a Premium brand for MetaGym by Jay Cutler. Notable inclusions; a how-to section for new NFT buyers, video clips including Jay Cutler, and future of the project showcase.
            </RoadmapBody>
            <RoadmapBody>
              📆 - Launch a Discord specific to the NFT / Metaverse community. Mr. Cutler will drop in once in a while and engage with the community.
            </RoadmapBody>
            <RoadmapBody>
              💰 - Launch an exclusive clothing line that drops ships from the website. Allow people to tweet / Instagram / etc., the merchandise purchase and get a premier WHITELIST spot for the project. Limit to first: 1000 sales.
            </RoadmapBody>
          </div>
          <div class="roadmap mt-8 md:mt-0">
            <RoadmapHeader>Q2 - 2022</RoadmapHeader>
            <RoadmapBody>🎯 - APRIL/MAY - We launch this NFT Collection on the Ethereum Blockchain as ERC-721 NFT's at a set minting price - to be determined depending on market conditions.</RoadmapBody>
            <RoadmapBody>📆 - After the sale of the NFT collection, 25% of proceeds will acquire digital land in the Metaverse to bring to life the vision of the first of its kind - Jay Cutler's MetaGym(TM)</RoadmapBody>
            <RoadmapBody>💻 - The MetaGym(TM) development continues with the latest technologies to bring the most immersive and interactive experience that technology currently allows. </RoadmapBody>
            <RoadmapBody>
              💎 - Jay Cutler loves nothing more than his loyal fans, and to show this, fans holding his NFT's will get a chance to win a trip to meet Jay and workout, the ultimate VIP experience! Others will get an opportunity to meet Jay on group calls/chats in the exclusive community both online and in the future Metaverse.
            </RoadmapBody>
            <RoadmapBody>💰- Jay believes in giving back and wants to donate 10% to the Make a Wish Foundation.</RoadmapBody>
          </div>
          <div class="roadmap mt-8 md:mt-0">
            <RoadmapHeader>Q3 & Q4 - 2022</RoadmapHeader>
            <RoadmapBody>🎯 - Construction begins for our new home clubhouse in the Metaverse. We can't wait to reveal the immersive areas and special floors dedicated to NFT holders only!</RoadmapBody>
            <RoadmapBody>
              💻 - Future expansion plans revealed for the Metaverse and clubhouse exclusive to MetaGym by Jay Cutler NFT holders.
            </RoadmapBody>
          </div>
        </div>
      </SectionBody>
    </section>
    <section class="section">
      <SectionHeader anchor="the-team">The Team</SectionHeader>
      <SectionBody>
        <div class="grid grid-cols-2 md:grid-cols-3 gap-11">
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
