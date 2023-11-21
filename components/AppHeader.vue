<template>
  <div>
    <div
      class="flex container justify-between mx-auto md:py-8 md:p-0 p-8"
    >
      <div class="flex gap-3 md:gap-0">
        <div class="md:hidden block" id="navbar">
          <!-- Testing -->
          <UButton
            icon="i-heroicons-bars-3"
            size="sm"
            color="primary"
            square
            variant="solid"
          />
        </div>
        <!--  -->

        <h1
          class="md:text-3xl text-2xl text-primary font-semibold"
          id="web-name"
        >
          rstubryan
        </h1>
      </div>
      <div class="flex">
        <div id="nav-menu">
          <ul class="md:flex gap-10 py-1 hidden">
            <NuxtLink to="" class="text-primary border-b border-primary"
              >Home</NuxtLink
            >
            <NuxtLink to="">About</NuxtLink>
            <NuxtLink to="">Portofolio</NuxtLink>
            <NuxtLink to="">Blog</NuxtLink>
            <NuxtLink to="">Contact</NuxtLink>
          </ul>
        </div>
        <div class="pl-10" id="color-mode">
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
