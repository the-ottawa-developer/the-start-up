<template>
  <div class="bg-white">
    <div class="min-h-screen flex flex-col">
      <!-- header content goes here -->
      <slot name="header" />
      <!-- Main content -->
      <main class="flex-1">
        <slot />
      </main>
      <!-- Footer content goes here -->
      <slot name="footer" />
    </div>
  </div>
</template>

<style>
/* No custom styles needed */
</style>
