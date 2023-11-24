<template>
  <div>
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
            class="w-20 z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
        <div id="js">
          <NuxtImg
            src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png"
            class="w-16 z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
        <div id="vue">
          <NuxtImg
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1280px-Vue.js_Logo_2.svg.png"
            class="w-16 z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
        <div id="nuxt">
          <NuxtImg
            src="https://nuxt.com/assets/design-kit/icon-green.png"
            class="w-24 z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
        <div id="php">
          <NuxtImg
            src="https://www.php.net//images/logos/new-php-logo.png"
            class="w-24= z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
        <div id="mysql">
          <NuxtImg
            src="https://www.mysql.com/common/logos/logo-mysql-170x115.png"
            class="w-24 z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
        <div id="laravel">
          <NuxtImg
            src="https://raw.githubusercontent.com/laravel/art/master/laravel-logo.png"
            class="w-20 z-50 hover:scale-150 transition duration-300 ease-in-out hover:animate-pulse"
          />
        </div>
      </div>
    </div>
  </div>
</template>
