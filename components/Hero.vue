<template>
  <section class="hero grid grid-cols-6 gap-8 sm:grid-cols-6 lg:grid-cols-12 flex md:px-0 items-center">
    <div class="relative flex flex-col items-center justify-start col-span-6">
    <div class="hero--container">
      <h1 class="hero--headings">
        <span class="block">Collect the OG's <span class="block text-gradient bg-gradient-to-r from-red-600 via-pink-400 to-yellow-300 inline lg:mt-0 mt-1">101PXL</span> NFTs</span>
      </h1>
      <p class="sm:text-left md:text-left lg:text-center">
        1111 left-side pfp NFTs living on the Tezos blockchain. Each piece is unique programmatically generated from over 85+ hand-drawn traits. Built with Manga style in pixel art.
      </p>
      <div class="hero--actions md:space-x-4">
        <a href="#" class="btn bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500 text-white" target="_blank">
          Coming Soon
        </a>
      </div>
    </div>
    </div>
    
    <div class="relative flex flex-col items-center justify-start col-span-6">
    <div class="my-4">
      <img src="~/assets/images/animated_101pxl.gif" alt="101PXL Nft" class="w-1/2 mx-auto">
    </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style lang="postcss" scoped>
.hero {
  @apply px-2 pt-32 pb-10 bg-white;
}

.hero .hero--container {
  @apply container items-center max-w-6xl px-5 mx-auto space-y-6 text-center;
}

.hero .hero--headings {
  @apply text-4xl font-extrabold tracking-tight text-accent text-left;

  @screen sm {
    @apply text-5xl;
  }

  @screen md {
    @apply text-6xl text-center;
  }
}

.hero .hero--description {
  @apply w-full mx-auto text-base text-left text-gray-500;

  @screen sm {
    @apply text-lg;
  }

  @screen md {
    @apply max-w-md text-center;
  }

  @screen lg {
    @apply text-2xl;
  }
}

.hero .hero--actions {
  @apply relative flex flex-col justify-center;

  @screen lg {
    @apply flex-row space-x-4;
  }
}

.hero .hero--img-container {
  @apply container items-center max-w-4xl px-5 mx-auto mt-16 text-center;
}

.hero .btn {
  @apply px-6 py-3 mb-3 text-lg rounded-md;
}
</style>
