<template>
  <div>
    <div class="flex container justify-between mx-auto w-[1200px] py-8">
      <div class="flex">
        <h1 class="text-3xl text-primary font-semibold">rstubryan</h1>
      </div>
      <div class="flex">
        <div class="">
          <ul class="flex gap-10 py-1">
            <NuxtLink to="" class="text-primary border-b border-primary"
              >Home</NuxtLink
            >
            <NuxtLink to="">About</NuxtLink>
            <NuxtLink to="">Portofolio</NuxtLink>
            <NuxtLink to="">Blog</NuxtLink>
            <NuxtLink to="">Contact</NuxtLink>
          </ul>
        </div>
        <div class="pl-10">
          <ColorScheme v-model="$colorMode.preference">
            <div>
              <UButton
                :icon="
                  $colorMode.preference === 'light'
                    ? 'i-heroicons-moon'
                    : 'i-heroicons-sun'
                "
                size="sm"
                color="primary"
                square
                variant="solid"
                @click="
                  $colorMode.preference =
                    $colorMode.preference === 'light' ? 'dark' : 'light'
                "
              />
            </div>
          </ColorScheme>
        </div>
      </div>
    </div>
  </div>
</template>
