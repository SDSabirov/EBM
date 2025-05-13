<template>
  <div
    class="relative min-h-screen bg-repeat bg-center"
    style="background-image: url('/bg-pattern.png');"
  >
    <!-- Overlay -->
    <div class="absolute inset-0 bg-black bg-opacity-50"></div>

    <!-- Centered Content -->
    <div class="relative z-10 flex flex-col items-center justify-center h-screen px-4">
      <!-- Logo -->
      <img src="/logowhite.png" alt="Logo" class="h-64  mb-6" />

      <!-- Headline -->
      <h1 class="text-5xl font-extrabold text-white mb-2">Coming Soon</h1>

      <!-- Subtext -->
      <p class="text-lg text-white text-center max-w-md">
        We're working hard behind the scenes to bring you something amazing. Stay tuned!
      </p>
    </div>
  </div>
</template>
<script setup lang="ts">
// Set page title

</script>

<style scoped>
/* Add any page-specific styling here */
</style>