<template>
  <nav class="bg-gray-800 p-4">
    <router-link class="text-white hover:text-gray-300 mr-4" to="/">Home</router-link> |
    <router-link class="text-white hover:text-gray-300 ml-4" to="/about">About</router-link>
  </nav>
  <main class="p-4">
    <router-view />
  </main>
</template>