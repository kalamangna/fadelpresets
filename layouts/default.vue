<template>
  <div>
    <!-- HEADER -->
    <nav class="p-4 bg-gray-800 text-white">
      <div class="font-bold">
        FADELPRESETS
      </div>
    </nav>

    <div class="container mx-auto p-8">
      <Nuxt />
    </div>

    <!-- FOOTER -->
    <footer class="p-2 bg-gray-800 text-white text-sm w-full fixed bottom-0">
      &copy; {{ new Date().getFullYear() }} -
      <a href="https://github.com/kalamangna" target="_blank"
        >github.com/kalamangna</a
      >
    </footer>
  </div>
</template>
