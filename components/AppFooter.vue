<template>
  <div>
    <div class="">
      <div
        class="container mx-auto md:h-72 h-[500px] md:py-14 py-8 p-8 md:p-0 md:flex md:justify-between"
      >
        <div class="md:flex">
          <div>
            <h2 class="text-2xl font-bold text-primary">Get in touch</h2>
            <div class="flex">
              <div
                class="text-base py-4 leading-8 w-72 hover:animate-pulse flex"
              >
                <div class="py-1 mr-2">
                  <UIcon
                    name="i-heroicons-envelope"
                    class="hover:animate-pulse text-2xl text-primary flex"
                  ></UIcon>
                </div>
                <div>
                  <NuxtLink
                    to="mailto:restubumirr@gmail.com"
                    class="flex"
                    target="_blank"
                    >restubumirr@gmail.com
                  </NuxtLink>
                </div>
              </div>
            </div>
          </div>
          <div class="">
            <h2 class="text-2xl font-semibold text-primary">Connect</h2>
            <ul class="grid leading-8 py-4 text-base">
              <NuxtLink
                to="https://www.linkedin.com/in/rstubryan/"
                class="hover:animate-pulse"
                target="_blank"
                >LinkedIn</NuxtLink
              >
              <NuxtLink
                to="https://discordapp.com/users/554985727327207424"
                class="hover:animate-pulse"
                target="_blank"
                >Discord</NuxtLink
              >
              <NuxtLink
                to="https://www.instagram.com/zedexzs/"
                class="hover:animate-pulse"
                target="_blank"
                >Instagram</NuxtLink
              >
              <NuxtLink
                to="https://www.facebook.com/hideyoshi.hideyoshi.3386"
                class="hover:animate-pulse"
                target="_blank"
                >Facebook</NuxtLink
              >
            </ul>
          </div>
        </div>
        <div class="md:flex gap-10">
          <div>
            <h2 class="text-2xl font-semibold text-primary">Blog (Soon)</h2>
            <ul class="grid leading-8 py-4 text-base">
              <NuxtLink to="" class="hover:animate-pulse">Nuxt 3</NuxtLink>
              <NuxtLink to="" class="hover:animate-pulse">Vue 3</NuxtLink>
            </ul>
          </div>
        </div>
      </div>
      <hr class="container mx-auto border-primary" />
      <div class="">
        <p class="text-center py-8">
          &copy; 2023 <span class="text-primary font-bold">rstubryan</span>. All
          rights reserved.
        </p>
      </div>
    </div>
  </div>
</template>
