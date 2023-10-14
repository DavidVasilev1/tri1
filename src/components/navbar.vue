<script setup lang="ts">
  import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="navbar bg-base-100">
    <RouterLink to="/home" class="flex items-center ml-5">
      <img src="/src/assets/images/logo.png" class="h-16" alt="Flowbite Logo" />
    </RouterLink>

    <div class="md:flex space-x-10 mr-20">
      <RouterLink to="/app" class="btn btn-ghost ml-16">APP</RouterLink>
      <RouterLink to="/game" class="btn btn-ghost">GAME</RouterLink>
    </div>


    <div class="navbar-end md:ml-auto md:mr-10">
      <RouterLink to="/about" class="btn btn-ghost">ABOUT</RouterLink>
    </div>
  </div>
</template>