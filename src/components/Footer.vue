<template>
  <footer class="overflow-hidden bg-neutral-950 text-white py-6 px-6 pl-28 pr-28 flex justify-between items-center">
    <div class="flex flex-col items-start gap-2">
      <div class="flex items-center gap-3">
        <div class="font-bold text-lg">Juliana Moreno</div>
      </div>
      <div class="text-sm max-w-sm">Futura desenvolvedora, explorando o mundo do front-end.</div>
    </div>
    <div class="flex gap-6">
      <a href="https://www.instagram.com/juliana_moren0/" target="_blank" aria-label="Instagram">
        <img src="/LogoInstagram.png" alt="Instagram" class="w-8 h-8 hover:scale-110 transition duration-100" />
      </a>
      <a href="https://github.com/juliana-mt" target="_blank" aria-label="GitHub">
        <img src="/logoGithub.png" alt="GitHub" class="w-8 h-8 hover:scale-110 transition duration-100" />
      </a>
      <a href="https://www.linkedin.com/in/juliana-moreno-torres-1614b8312/" target="_blank" aria-label="LinkedIn">
        <img src="/logoLinkedIn.png" alt="LinkedIn" class="w-8 h-8 hover:scale-110 transition duration-100" />
      </a>
    </div>
  </footer>

  <p class=" text-xs text-center w-full bg-rose-800 text-white px-4 py-2">
      © Copyright 2025. Feito por <strong class="cursor-pointer">Juliana Moreno</strong>.
  </p>
</template>

<script>
export default {
  name: 'Footer'
}
</script>