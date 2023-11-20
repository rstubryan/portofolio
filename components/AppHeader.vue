<template>
  <div>
    <div class="flex container justify-between mx-auto w-[1200px]">
      <div class="flex">
        <h1 class="text-2xl text-primary">rstubryan</h1>
      </div>
      <div class="flex">
        <div class="">
          <ul class="flex gap-10">
            <NuxtLink to="/login">Home</NuxtLink>
            <NuxtLink to="/login">About</NuxtLink>
            <NuxtLink to="/login">Portofolio</NuxtLink>
            <NuxtLink to="/login">Blog</NuxtLink>
            <NuxtLink to="/login">Contact</NuxtLink>
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
