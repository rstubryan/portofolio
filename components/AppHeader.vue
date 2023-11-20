<template>
  <div>
    <div class="flex container justify-between mx-auto w-[1200px] py-8">
      <div class="flex">
        <h1 class="text-3xl text-primary font-semibold">rstubryan</h1>
      </div>
      <div class="flex">
        <div class="">
          <ul class="flex gap-10">
            <NuxtLink to="">Home</NuxtLink>
            <NuxtLink to="">About</NuxtLink>
            <NuxtLink to="">Portofolio</NuxtLink>
            <NuxtLink to="">Blog</NuxtLink>
            <NuxtLink to="">Contact</NuxtLink>
          </ul>
        </div>
        <div class="flex gap-10">
          <ColorScheme
            ><USelect
              v-model="$colorMode.preference"
              :options="['system', 'light', 'dark']"
          /></ColorScheme>
        </div>
      </div>
    </div>
  </div>
</template>
