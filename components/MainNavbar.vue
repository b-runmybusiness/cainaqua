<template>
  <nav class='bg-white w-full py-2 border-b border-gray-200'>
    <div class='px-4 flex justify-between max-w-5xl w-full mx-auto'>
      <div class='logo flex gap-3 items-center'>
        <img src="/images/logo.jpeg" alt="cainaqua-logo" class="h-14 w-full object-contain" />
      </div>
      <div class='flex items-center gap-2 text-zinc-900'>
        <NuxtLink to="/" class='rounded px-3 py-1 text-sm'>Home</NuxtLink>
        <NuxtLink to="/about" class='rounded px-3 py-1 text-sm'>About</NuxtLink>
        <a href='#' class='rounded px-3 py-1 text-sm'>Products</a>
        <NuxtLink to="/contact" class='rounded px-3 py-1 text-sm'>Contact</NuxtLink>
      </div>
    </div>
  </nav>
  <!-- quick nav links -->
  <div class="flex items-center gap-10 justify-center text-sm bg-gray-800  text-gray-100 font-semibold py-2">
      <NuxtLink to="/" class="">Alkaline RO Purifier</NuxtLink>
      <NuxtLink to="/">Hot & Cold RO</NuxtLink>
      <NuxtLink to="/">Softener</NuxtLink>
      <NuxtLink to="/">Ionizer</NuxtLink>
      <NuxtLink to="/">Kitchen Appliance</NuxtLink>
    </div>
</template>

<script setup>

</script>

<style>

</style>