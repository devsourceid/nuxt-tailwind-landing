<template>
  <header class="toolbar">
    <div class="toolbar--container">
      <NuxtLink to="/" class="text--logo text-gradient bg-gradient-to-r from-red-600 via-pink-400 to-yellow-300">
        101PXL
      </NuxtLink>

      <div class="relative z-10 inline-flex items-center space-x-3 md:ml-5 lg:justify-end">
        <nav class="hidden md:block">
          <div class="flex items-baseline space-x-10">
            <!-- <a href="#_" class="item--link">
              <span class="block">Home</span>
            </a> -->
            <span class="inline-flex rounded-md shadow-sm">
              <a href="#" class="btn bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500 text-white">
                MINT NFT
              </a>
            </span>
          </div>
        </nav>

      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style lang="postcss" scoped>
.toolbar {
  @apply relative w-full px-8 text-gray-700 bg-white;
}

.toolbar .toolbar--container {
  @apply container flex flex-col flex-wrap items-center justify-between py-5 mx-auto max-w-7xl;

  @screen md {
    @apply flex-row;
  }
}

.toolbar .text--logo {
  @apply relative z-10 flex items-center w-auto text-2xl font-extrabold leading-none select-none;
}

nav .item--link {
  @apply relative font-medium leading-6 mx-2 text-gray-600 transition duration-150 ease-out;
}

nav .item--link:hover {
  @apply text-gray-900;
}
</style>
