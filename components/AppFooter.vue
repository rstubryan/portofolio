<template>
  <div>
    <div class="bg-primary">
      <div
        class="container mx-auto md:h-72 h-[500px] md:py-14 py-8 p-8 md:p-0 md:flex md:justify-between"
      >
        <div class="md:flex">
          <div>
            <h2 class="text-2xl font-bold text-white">Get in touch</h2>
            <p
              class="text-base text-gray-100 py-4 leading-8 w-72 hover:animate-pulse"
            >
              restubumirr@gmail.com
            </p>
          </div>
          <div class="">
            <h2 class="text-2xl font-semibold text-white">Connect</h2>
            <ul class="grid leading-8 py-4 text-base text-white">
              <NuxtLink to="" class="hover:animate-pulse">LinkedIn</NuxtLink>
              <NuxtLink to="" class="hover:animate-pulse">Discord</NuxtLink>
              <NuxtLink to="" class="hover:animate-pulse">Instagram</NuxtLink>
              <NuxtLink to="" class="hover:animate-pulse">Facebook</NuxtLink>
            </ul>
          </div>
        </div>
        <div class="md:flex gap-10">
          <div>
            <h2 class="text-2xl font-semibold text-white">Blog</h2>
            <ul class="grid leading-8 py-4 text-base text-white">
              <NuxtLink to="" class="hover:animate-pulse">Nuxt 3</NuxtLink>
              <NuxtLink to="" class="hover:animate-pulse">Vue 3</NuxtLink>
            </ul>
          </div>
        </div>
      </div>
      <div class="dark:bg-primary-500 bg-primary-600">
        <p class="text-center text-gray-100 py-4">
          &copy; 2023 rstubryan. All rights reserved.
        </p>
      </div>
    </div>
  </div>
</template>
