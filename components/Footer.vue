<template>
  <footer class="footer">
    <div class="footer--container">
      <div class="w-full flex flex-wrap justify-between items-start mb-10">

        <div class="w-full lg:w-6/12 px-4">
          <div class="w-1/2">
            <NuxtLink to="/" class="text--logo">
              101PXL
            </NuxtLink>
          </div>
          <div class="my-2">
            <h5 class="text-md my-0 text-gray-600">1111 left-side pfp NFTs living on the Solana blockchain.</h5>
          </div>
        </div>

        <div class="w-full lg:w-4/12 px-4">
          <div class="w-full flex-wrap flex justify-between items-start">

            <div class="w-full lg:w-6/12 ml-auto">
              <ul class="list-none text-md">
                <li class="mb-2 font-semibold uppercase block">
                  Stay Updates
                </li>
                <li class="mb-2 block  text-gray-600">
                  <a href="https://twitter.com/101PXL" target="_blank">Twitter</a>
                </li>
                <li class="mb-2 block text-gray-600">
                  <a href="https://solsea.io/collection/620e8d74130c9f4471197762" target="_blank">SolSea Collection</a>
                </li>
              </ul>
            </div>


          </div>
        </div>

      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="postcss" scoped>
.footer {
  @apply relative shadow-inner bg-gray-50 pt-16 pb-6;
}

.footer .footer--container {
  @apply container mx-auto max-w-7xl;

  @screen md {
    @apply flex-row;
  }
}

.footer .text--logo {
  @apply relative z-10 flex items-center w-auto text-2xl font-extrabold leading-none text-accent select-none;
}
</style>
