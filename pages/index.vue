<template>
  <div>
    <!-- Hero Start -->
    <Hero />
    <!-- Hero End -->

    <!-- Features Start -->
    <section class="py-20 bg-gray-50 shadow-inner">
      <div class="px-4 mx-auto text-center max-w-7xl sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold tracking-tight text-accent sm:text-4xl md:text-5xl xl:text-6xl">
          The Species
        </h2>
        <p class="max-w-md mx-auto mt-3 text-base text-gray-500 sm:text-lg md:mt-5 md:text-xl md:max-w-3xl">
          There are 4 species on 101PXL NFTs.
        </p>
      </div>

      <div class="container max-w-6xl mx-auto">
        <div class="grid grid-cols-3 gap-8 mt-10 sm:grid-cols-3 lg:grid-cols-12 sm:px-8 xl:px-0">
          <div class="relative flex flex-col items-center justify-start col-span-3 px-8 py-12 space-y-4 overflow-hidden">
            <div class="p-3 text-white">
              <img src="~/assets/images/human.png" alt="101PXL Nft" class="w-1/2 mx-auto">
            </div>
            <h4 class="text-xl font-medium text-accent">
              Human
            </h4>
            <p class="text-base text-center text-gray-500">
              Humans must survive amid the threat of Zombies and Monsters that rule the world.
            </p>
          </div>

          <div class="relative flex flex-col items-center justify-start col-span-3 px-8 py-12 space-y-4 overflow-hidden">
            <div class="p-3 text-white">
              <img src="~/assets/images/zombie.png" alt="101PXL Nft" class="w-1/2 mx-auto">
            </div>
            <h4 class="text-xl font-medium text-accent">
              Zombie
            </h4>
            <p class="text-base text-center text-gray-500">
              The main enemies are Humans and Cyborgs with high survivability.
            </p>
          </div>

          <div class="relative flex flex-col items-center justify-start col-span-3 px-8 py-12 space-y-4 overflow-hidden">
            <div class="p-3 text-white">
              <img src="~/assets/images/cyborg.png" alt="101PXL Nft" class="w-1/2 mx-auto">
            </div>
            <h4 class="text-xl font-medium text-accent">
              Cyborg
            </h4>
            <p class="text-base text-center text-gray-500">
              Cyborgs were created to help humans defend populations from extinction.
            </p>
          </div>

          <div class="relative flex flex-col items-center justify-start col-span-3 px-8 py-12 space-y-4 overflow-hidden">
            <div class="p-3 text-white">
              <img src="~/assets/images/monster.png" alt="101PXL Nft" class="w-1/2 mx-auto">
            </div>
            <h4 class="text-xl font-medium text-accent">
              Monster
            </h4>
            <p class="text-base text-center text-gray-500">
              Monsters are evolved Zombies, with higher speed, intelligence and survivability.
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- Features End -->

    <!-- Testimonials Start-->
    <Testimonials :testimonials="testimonials"/>
    <!-- Testimonials End-->

    <!-- Call To Action Start -->
    <CallAction />
    <!-- Call To Action End -->
  </div>
</template>

<script>
import Hero from '~/components/Hero.vue';
import Testimonials from '~/components/Testimonials.vue';
import CallAction from '~/components/CallAction.vue';

export default {
  components: {
    Hero,
    Testimonials,
    CallAction
  },
  head: {
    title: '101PXL NFT - 1 0f 1 Collectible Pixel NFTs',
    meta: [ // SEO Tags
      {
        hid: 'description',
        name: 'description',
        content: '101PXL NFT - 1 0f 1 Collectible Pixel NFTs'
      }
    ]
  },
  data: () => ({
    testimonials: [
      {
        id: 1,
        message: 'A unique avatar to be used everywhere to stand out on the Solana blockchain.'
      },
      {
        id: 2,
        message: 'Become a 101PXL Collector. Buy, sell and trade safely. And get Exclusive NFT every launch new version.'
      },
      {
        id: 3,
        message: 'Be part of the new NFT community of the Solana ecosystem.'
      }
    ]
  })
}
</script>

<style lang="postcss" scoped>
body {
  font-family: 'Press Start 2P', cursive;
}
</style>