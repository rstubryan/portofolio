<template>
  <div>
    <div
      class="container mx-auto md:h-96 md:px-0 px-8 md:py-0 py-8 justify-between"
      id="blog"
    >
      <div class="md:flex">
        <div class="w-full md:w-[700px] mx-auto">
          <div class="bg-primary rounded-full">
            <div id="blog-icon" class="mt-12">
              <NuxtImg
                src="https://raw.githubusercontent.com/rstubryan/assets/35a216855d85d98b8d333cb56135f6da8f210496/gambar/portofolio/blog.svg"
                class="w-72 z-50 items-center justify-center mx-auto"
              />
            </div>
          </div>
        </div>
        <div class="md:py-[60px] py-4 md:pl-32">
          <div class="md:text-start text-center py-4">
            <h2 class="md:text-5xl text-3xl font-bold text-primary">Blog</h2>
            <p
              class="md:text-lg text-base font-semibold py-6 text-gray-600 dark:text-gray-400"
            >
              My <span class="text-primary">blog</span> is currently in the
              process of being built. Please wait for the next update!
            </p>
            <div class="">
              <NuxtLink to="https://rstubryan-blog.vercel.app/" target="_blank">
                <UButton
                  icon="md:i-heroicons-arrow-left i-heroicons-arrow-up"
                  size="xl"
                  color="primary"
                  variant="solid"
                  label="Blog"
                  :trailing="false"
                />
              </NuxtLink>
            </div>
            <h3 class="py-4 text-gray-600 dark:text-gray-400">
              Powered by : Nuxt <span class="text-primary">Content</span>
            </h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
