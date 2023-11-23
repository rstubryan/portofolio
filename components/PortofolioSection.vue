<template>
  <div>
    <!-- <div class="flex items-center justify-center px-16">
      <div class="relative w-full max-w-lg">
        <div
          class="absolute md:-bottom-52 -bottom-80 md:-left-96 right-32 w-72 h-72 bg-primary-500 rounded-full mix-blend-multiply filter blur-xl dark:opacity-30 opacity-70 animate-blob"
        ></div>
        <div
          class="absolute md:top-82 -bottom-96 md:-left-96 w-72 h-72 bg-primary-300 rounded-full mix-blend-multiply filter blur-xl dark:opacity-30 opacity-70 animate-blob animation-delay-2000"
        ></div>
        <div
          class="absolute md: -top-10 md:right-72 -right-20 w-72 h-72 bg-primary-400 rounded-full mix-blend-multiply filter blur-xl dark:opacity-30 opacity-70 animate-blob animation-delay-4000"
        ></div>
      </div>
    </div> -->
    <div class="container mx-auto h-96">
      <div class="text-center py-4">
        <h2 class="text-5xl font-bold">Portofolio</h2>
        <h3 class="text-lg font-semibold py-6">
          My <span class="text-primary">tech stack</span> and
          <span class="text-primary">projects</span> I've worked on so far
        </h3>
      </div>
      <div class="flex mx-auto items-center justify-center py-4 gap-12">
        <div id="tailwind">
          <NuxtImg
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/512px-Tailwind_CSS_Logo.svg.png"
            class="w-28 z-50 hover:scale-150 transition duration-300 ease-in-out"
          />
        </div>
        <div id="js">
          <NuxtImg
            src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png"
            class="w-24 z-50 hover:scale-150 transition duration-300 ease-in-out"
          />
        </div>
        <div id="vue">
          <NuxtImg
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1280px-Vue.js_Logo_2.svg.png"
            class="w-24 z-50 hover:scale-150 transition duration-300 ease-in-out"
          />
        </div>
        <div id="nuxt">
          <NuxtImg
            src="https://nuxt.com/assets/design-kit/icon-green.png"
            class="w-32 z-50 hover:scale-150 transition duration-300 ease-in-out"
          />
        </div>
        <div id="laravel">
          <NuxtImg
            src="https://raw.githubusercontent.com/laravel/art/master/laravel-logo.png"
            class="w-28 z-50 hover:scale-150 transition duration-300 ease-in-out"
          />
        </div>
        <div id="mysql">
          <NuxtImg
            src="https://www.mysql.com/common/logos/logo-mysql-170x115.png"
            class="w-28 z-50 hover:scale-150 transition duration-300 ease-in-out"
          />
        </div>
      </div>
    </div>
  </div>
</template>
