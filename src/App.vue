<template>
  <div class="flex flex-col min-h-screen">
    <!-- Header -->
    <header class="flex items-center h-16 px-6 bg-white border-b border-gray-300 shadow">
      <div>
        <a class="flex items-center gap-2 font-semibold" href="#">
          <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="40" height="40" />
          <span class="text-lg font-bold">Mi Sitio Web</span>
        </a>
      </div>
      <nav class="ml-auto space-x-6 flex items-center h-full">
        <RouterLink to="/" class="hover:text-blue-500">Principal</RouterLink>
        <RouterLink :to="{ name: 'FeaturesPagina' }" class="hover:text-blue-500">Feature</RouterLink>
        <RouterLink :to="{ name: 'ContactoPagina' }" class="hover:text-blue-500">Contacto</RouterLink>
        <RouterLink :to="{ name: 'PreciosPagina' }" class="hover:text-blue-500">Precio</RouterLink>
      </nav>
    </header>
    <!-- Fin Header -->

    <!-- Main -->
    <main class="flex-grow">
      <RouterView />
    </main>
    <!-- Fin Main -->

    <!-- Footer -->
    <footer class="flex items-center h-16 px-6 bg-gray-100 border-t border-gray-300">
      <p class="text-sm text-gray-500 text-center w-full">
        © 20xx Acme Corporation. Derechos reservados.
      </p>
    </footer>
    <!-- Fin Footer -->
  </div>
</template>

<script lang="ts" setup>
</script>
