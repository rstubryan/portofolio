<template>
  <div>
    <div
      class="container mx-auto md:px-0 px-8 md:py-[230px] py-8 md:flex"
      id="hero"
    >
      <div class="z-50">
        <div class="">
          <h3 class="font-bold md:text-2xl text-xl py-4">Hello!</h3>
          <h2 class="md:text-7xl text-4xl font-semibold md:w-[700px]">
            I'm
            <span class="text-primary font-bold">Restu</span> Bumi Ryan Ramadhan
            <h3 class="text-primary font-bold md:text-3xl text-xl py-4">
              Front<span class="text-black dark:text-white">-</span>End
              <span class="text-black dark:text-white">Developer</span>
            </h3>
            <p
              class="md:text-lg text-base text-gray-600 dark:text-gray-400 w-full md:w-[600px] py-2 leading-loose text-justify"
            >
              I'm a
              <span class="text-black dark:text-white"
                >junior web developer</span
              >
              in the process of growth, eager to learn more, especially in
              developing websites with
              <span class="text-primary"
                >Nuxt 3
                <span class="dark:text-white text-black">&</span> Tailwind
                CSS</span
              >.
            </p>
          </h2>
        </div>
        <div class="py-4">
          <UButton
            icon="i-heroicons-arrow-down"
            size="xl"
            color="primary"
            variant="solid"
            label="Let's Go!"
            :trailing="false"
          />
        </div>
      </div>
      <div class="mx-auto md:flex md:py-0 py-4">
        <div class="flex items-center justify-center px-16">
          <div class="relative w-full max-w-lg">
            <div
              class="absolute md:-bottom-52 -bottom-40 md:-right-48 right-32 md:w-72 w-32 md:h-72 h-32 bg-primary-500 rounded-full mix-blend-multiply filter blur-xl dark:opacity-100 opacity-70 animate-blob"
            ></div>
            <div
              class="absolute md:top-0 -bottom-96 md:left-72 md:w-72 w-32 md:h-72 h-32 bg-primary-300 rounded-full mix-blend-multiply filter blur-xl dark:opacity-100 opacity-70 animate-blob animation-delay-2000"
            ></div>
            <div
              class="absolute md:-top-72 -top-10 md:left-72 -right-20 md:w-72 w-32 md:h-72 h-32 bg-primary-400 rounded-full mix-blend-multiply filter blur-xl dark:opacity-100 opacity-70 animate-blob animation-delay-4000"
            ></div>
          </div>
        </div>
        <div class="flex justify-center items-center z-50">
          <NuxtImg
            src="https://avatars.githubusercontent.com/u/96672455?v=4"
            alt="Restu Bumi Ryan Ramadhan"
            class="rounded-full md:w-[420px] w-[320px] border-8 border-primary z-50"
          />
        </div>
      </div>
    </div>
    <hr class="border-gray-100 dark:border-gray-900" />
  </div>
</template>
