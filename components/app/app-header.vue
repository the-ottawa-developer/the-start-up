<script setup lang="ts">
</script>

<template>
  <header class="absolute inset-x-0 top-0 z-50">
    <nav
      class="flex items-center justify-between p-6 lg:px-8"
      aria-label="Global"
    >
      <div class="flex lg:flex-1">
        <a
          href="#"
          class="-m-1.5 p-1.5"
        >
          <span class="sr-only">Your Company</span>
          <img
            class="h-8 w-auto"
            src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600"
            alt=""
          >
        </a>
        <!-- Site logo -->
        <nuxt-link
          to="/"
          class="flex items-center"
        >
          <span class="ml-3 text-slate-800 font-bold text-xl">Better Ottawa</span>
        </nuxt-link>
      </div>
      <div class="hidden lg:flex lg:gap-x-12" />
      <div class="hidden lg:flex lg:flex-1 lg:justify-end">
        <a
          href="#"
          class="sr-only text-sm font-semibold leading-6 text-gray-900"
        >Log in <span aria-hidden="true">&rarr;</span></a>
      </div>
    </nav>
  </header>

  <div
    v-if="false"
    class="bg-gray-400 z-50"
  >
    <header>
      <u-container>
        <div class="flex items-center justify-between py-6 lg:py-8">
          <h2 class="sr-only">
            Site header
          </h2>

          <nav class="flex lg:flex-1">
            <h3 class="sr-only">
              Site navigation
            </h3>
          </nav>
        </div>
      </u-container>
    </header>
  </div>
</template>

<style>
/* No custom styles needed */
</style>
