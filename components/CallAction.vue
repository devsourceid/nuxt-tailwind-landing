<template>
  <section class="call--action">
    <div class="call--container">
      <div class="px-4 text-left text-white max-w-7xl sm:px-6 lg:px-8">
        <h2 class="call--heading">
          <span class="block">Get the Rare NFTs</span>
        </h2>
        <p class="call--subheading">
          All of NFTs just made 1 of 1, it has attributes that make them unique according to a defined rarity system. Get your 101PXL now.
        </p>
      </div>
      <div class="lg:flex-shrink-0 lg:mt-0 text-center mt-4">
        <div class="inline-flex rounded-md shadow">
          <a href="https://objkt.com/collection/KT1EFhvvyZKcFAsoiNSMatLDHQNGMiDk9gHa" target="_blank" class="btn btn--action">
            View Collection
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'CalAction'
}
</script>

<style lang="postcss" scoped>
.call--action {
  @apply py-5 bg-gradient-to-r from-red-600 via-pink-400 to-yellow-300;
}

.call--action .btn--action {
  @apply px-5 py-3 border border-transparent text-primary bg-white;
}

.call--action .call--container {
  @apply max-w-7xl mx-auto py-12 px-4;

  @screen sm {
    @apply px-6;
  }

  @screen lg {
    @apply flex items-center justify-between py-10;
  }
}

.call--action .call--heading {
  @apply text-3xl font-bold tracking-tight text-white;

  @screen sm {
    @apply text-4xl;
  }
}

.call--action .call--subheading {
  @apply max-w-md mx-auto text-base;

  @screen sm {
    @apply text-lg;
  }

  @screen md {
    @apply text-xl max-w-3xl;
  }
}
</style>

