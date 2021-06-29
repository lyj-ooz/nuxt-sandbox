<template>
  <div class="container box-border max-w-screen-lg mx-auto px-8">
    <nav class="bg-red-400 px-4 h-12 flex justify-between items-center">
      <NuxtLink to="/">home</NuxtLink>
      <NuxtLink to="/about">about</NuxtLink>
      <NuxtLink to="/contact">contact</NuxtLink>
      <NuxtLink to="/test">test</NuxtLink>
    </nav>
    <Nuxt />
  </div>
</template>

<style scoped>
.nuxt-link-exact-active {
  color: #64ffd3;
}
</style>
