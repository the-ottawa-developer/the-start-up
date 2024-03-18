<script setup lang="ts">
</script>

<template>
  <u-landing-hero
    title="Turn Your Vision into Reality"
    description="Watch your dreams materialize before your eyes with us."
  />
  <u-landing-section
    title="The freedom to build anything"
    description="Nuxt UI Pro ships with an extensive set of advanced components that cover a wide range of use-cases."
    :links="[{
      label: 'Explore components',
      color: 'gray',
      size: 'lg',
    }]"
    align="left"
  >
    <img
      src="https://picsum.photos/360/640"
      class="w-full rounded-md shadow-xl ring-1 ring-gray-300 dark:ring-gray-700"
    >
  </u-landing-section>

  <u-blog-list orientation="horizontal">
    <u-blog-post
      title="Nuxt 3.9"
      description="Nuxt 3.9 is out - a Christmas gift from the Nuxt team bringing Vite 5, interactive..."
    />
    <u-blog-post
      title="Nuxt DevTools 1.0"
      description="Nuxt DevTools v1.0 is out, generally available to all Nuxt projects!"
    />
    <u-blog-post
      title="Nuxt 3.8"
      description="Nuxt 3.8 is out, bringing built-in DevTools, automatic Nuxt Image install, a new app..."
    />
  </u-blog-list>
</template>

<style scoped>
/* No custom styles needed */
</style>
