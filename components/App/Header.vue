<script setup lang="ts">
import config from '../../app.config'
const isOpen = ref(false);

const title = config.defaultTitle

const menus = ref([
  {
    text: 'Home',
    to: '/',
  },
  {
    text: 'Store',
    to: '/store',
  },
  {
    text: 'Blog',
    to: '/blog',
  },
  {
    text: 'Dashboard',
    to: '/dashboard',
  },
]);
</script>

<template>
  <header class="bg-blue-600 text-white py-3 sm:py-5">
    <div
      class="container mx-auto pl-4 pr-2 sm:px-0 flex flex-row items-center gap-4 justify-between"
    >
      <NuxtLink to="/" class="font-bold text-white text-2xl">
        <!-- <img
          loading="lazy"
          src="/logo.svg"
          alt="Logo"
          class="max-w-full h-10"
        /> -->
        {{ title }}
      </NuxtLink>
      <button
        class="appearance-none px-2 py-2 rounded sm:hidden"
        type="button"
        aria-label="Menu"
        @click="isOpen = !isOpen"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>
      </button>
      <div
        :class="
          isOpen
            ? 'fixed sm:relative top-16 shadow sm:shadow-none left-4 right-4 rounded-lg overflow-hidden bg-white sm:bg-transparent py-2'
            : 'hidden sm:flex sm:w-6/12'
        "
      >
        <nav
          class="flex flex-col sm:relative w-full items-start sm:flex-row sm:justify-end sm:gap-1 sm:items-center"
        >
          <NuxtLink
            v-for="menu in menus"
            :key="menu.text"
            :to="menu.to"
            class="px-4 py-2 rounded-full w-full sm:w-auto text-gray-800 sm:text-white transition duration-200 font-medium hover:bg-white hover:text-blue-600"
            exact-active-class="bg-white !text-blue-600"
          >
            {{ menu.text }}
          </NuxtLink>
        </nav>
      </div>
    </div>
  </header>
</template>
