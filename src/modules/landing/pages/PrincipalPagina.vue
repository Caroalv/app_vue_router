<template>
  <div class="min-h-screen flex items-center justify-center bg-gradient-to-r from-blue-500 via-purple-500 to-pink-500">
    <div class="text-center">
      <h1 class="text-4xl md:text-6xl font-bold text-white animate-fade-in">
        ¡Bienvenido!
      </h1>
      <p class="mt-4 text-lg md:text-2xl text-gray-200">
        Es un placer tenerte aquí, ¡exploremos juntos!
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Principal",
};
</script>

<style scoped>
@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in {
  animation: fade-in 2s ease-in-out;
}
</style>
