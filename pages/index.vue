<template>
  <div class="">
    <nav class="bg-black backdrop-blur-xl fixed top-0 h-12 md:h-11 px-4 bg-opacity-70 w-full z-50">
      <div class="max-w-[990px] mx-auto h-12 md:h-11">
        <div class="flex items-center h-full">
          <div class="flex justify-between items-center w-full">
            <div class="mobile-menu inline-block md:hidden">
              <svg width="20" height="9" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M20 1H0V0h20v1zM20 9H0V8h20v1z" fill="#fff"/></svg>
            </div>
            <div class="logo opacity-70 hover:opacity-100 duration-500">
              <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="44" viewBox="0 0 16 44"><path d="M8.02 16.23c-.73 0-1.86-.83-3.05-.8-1.57.02-3.01.91-3.82 2.32-1.63 2.83-.42 7.01 1.17 9.31.78 1.12 1.7 2.38 2.92 2.34 1.17-.05 1.61-.76 3.03-.76 1.41 0 1.81.76 3.05.73 1.26-.02 2.06-1.14 2.83-2.27.89-1.3 1.26-2.56 1.28-2.63-.03-.01-2.45-.94-2.48-3.74-.02-2.34 1.91-3.46 2-3.51-1.1-1.61-2.79-1.79-3.38-1.83-1.54-.12-2.83.84-3.55.84zm2.6-2.36c.65-.78 1.08-1.87.96-2.95-.93.04-2.05.62-2.72 1.4-.6.69-1.12 1.8-.98 2.86 1.03.08 2.09-.53 2.74-1.31" fill="#fff"/></svg>
              </a>
            </div>
            <a class="nav-link" href="#">Mac</a>
            <a class="nav-link" href="#">iPad</a>
            <a class="nav-link" href="#">iPhone</a>
            <a class="nav-link" href="#">Watch</a>
            <a class="nav-link" href="#">TV</a>
            <a class="nav-link" href="#">Music</a>
            <a class="nav-link" href="#">Support</a>
            <div class="search text-white hidden md:inline-block opacity-70 hover:opacity-100 duration-500 cursor-pointer">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
              </svg>
            </div>
            <div class="bag text-white opacity-70 hover:opacity-100 duration-500 cursor-pointer">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
              </svg>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <main class="">
      <div class="covid bg-gray-100 mt-12 md:mt-11">
        <div class="container mx-auto py-3">
          <p class="text-sm text-gray-700 text-center px-6">We look forward to welcoming you to our stores. Whether you <a class="inline-link" href="#">shop in a store</a> or <a class="inline-link" href="#">shop online</a>, our Specialists can help you buy the products you love.</p>
        </div>
      </div>
      <div class="iphone bg-gray-50">
        <div class="container mx-auto pt-14 relative z-10">
          <div class="copy text-center">
            <h1 class="text-6xl font-medium tracking-tight text-gray-800">iPhone 12</h1>
            <h3 class="text-3xl text-gray-800 tracking-tight mt-2">Blast past fast.</h3>
            <p class="text-lg text-gray-500 mt-2">From $29.12/mo. for 24 mo. or $699 before trade‑in</p>
            <p class="text-lg text-gray-500">Buy directly from Apple with special carrier offers</p>
            <div class="links flex justify-center mt-3">
              <a href="#" class="flex group items-center text-blue-600">
                <span class="text-xl tracking-tight group-hover:underline">Learn more</span> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mt-1 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                </svg>
              </a>
              <a href="#" class="flex group ml-8 items-center text-blue-600">
                <span class="text-xl tracking-tight group-hover:underline">Buy</span> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mt-1 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div class="flex justify-center w-full -mt-8">
          <img class="w-[1200px] object-contain" src="../assets/iphone-12.jpg" alt="">
        </div>
      </div>
      <div class="iphone-pro bg-black">
        <div class="container mx-auto pt-14 relative z-10">
          <div class="copy text-center">
            <h1 class="text-6xl font-medium tracking-tight text-white">iPhone 12 Pro</h1>
            <h3 class="text-3xl text-white tracking-tight mt-2">It's a leap year.</h3>
            <p class="text-lg text-gray-100 mt-2">From $29.12/mo. for 24 mo. or $699 before trade‑in</p>
            <p class="text-lg text-gray-100">Buy directly from Apple with special carrier offers</p>
            <div class="links flex justify-center mt-3">
              <a href="#" class="flex group items-center text-blue-500">
                <span class="text-xl tracking-tight group-hover:underline">Learn more</span> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mt-1 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                </svg>
              </a>
              <a href="#" class="flex group ml-8 items-center text-blue-500">
                <span class="text-xl tracking-tight group-hover:underline">Buy</span> 
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mt-1 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div class="flex justify-center w-full -mt-8">
          <img class="w-[1200px] object-contain" src="../assets/iphone-12-pro.jpg" alt="">
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>

.nav-link {
  @apply text-white opacity-80 hidden md:inline-block hover:opacity-100 duration-500 text-sm tracking-wide font-light
}

a.inline-link {
  @apply text-blue-500 hover:underline
}



</style>