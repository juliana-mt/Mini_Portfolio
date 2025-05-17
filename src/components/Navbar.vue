<template>
  <nav class="overflow-hidden bg-neutral-950 p-4 text-white flex justify-between shadow-sm">
    <div class="flex items-center gap-3 hover:scale-105 transition duration-100 cursor-default">
        <img src="/public/foto.jpg" alt="juliana Moreno" class="w-10 h-10 rounded-full">
        <h1 class="font-bold text-xl hover:text-pink-400 shadow-sm">Juliana Moreno</h1>
    </div>
    <ul class="flex space-x-6 items-center">
      <li class="hover:scale-110 transition duration-100"><router-link to="/" class="hover:text-pink-600 cursor-pointer" exact>Home</router-link></li>
      <li class="hover:scale-110 transition duration-100"><router-link to="/sobre" class="hover:text-pink-600 cursor-pointer">Sobre</router-link></li>
      <li class="hover:scale-110 transition duration-100"><router-link to="/contato" class="hover:text-pink-600 cursor-pointer">Contato</router-link></li>
    </ul>
  </nav>
</template>

<script setup>

</script>
