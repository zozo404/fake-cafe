<script setup>
  import MenuIcon from './MenuIcon.vue';
</script>

<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <header class="bg-gray-900 lg:h-40 w-full z-20">
    <nav
      class="lg:max-h-40 w-full py-6 grid grid-cols-2 grid-rows-2 lg:grid-rows-1 lg:grid lg:grid-cols-3 items-center justify-between lg:border-none bg-gray-900"
      aria-label="Top"
    >
      <!-- logo -->
      <a href="/" class="flex justify-center lg:col-span-1 lg:h-full h-2/3">
        <span class="sr-only">Workflow</span>
        <img
          src="VRCAFE_LOGO_OK.webp"
          alt="logo vr café"
          class="h-full"
          sizes="xs:100vw"
        />
      </a>
      <!-- bouton réserver -->
      <div class="flex justify-center lg:col-start-3">
        <a
          href="reservation-simply.html"
          class="inline-block bg-white py-2 px-4 border border-transparent rounded-md text-base lg:text-2xl font-medium text-indigo-600 hover:bg-indigo-50"
          >Réserver</a
        >
      </div>
      <!-- navigation mobile -->
      <div
        class="col-span-2 lg:col-span-1 lg:col-start-2 lg:row-start-1 flex flex-col items-center"
      >
        <div class="mb-4 py-4 flex gap-4">
          <!-- acceuil -->
          <a
            key="Solutions"
            href="/"
            class="text-base lg:text-2xl font-medium text-white hover:text-indigo-50"
          >
            Accueil
            </a>
          <!-- tarifs -->
          <a
            key="Pricing"
            href="#price"
            class="text-base lg:text-2xl font-medium text-white hover:text-indigo-50"
          >
            Tarifs
          </a>
          <!-- services -->
          <a
            key="Pricing"
            href="#services"
            class="text-base lg:text-2xl font-medium text-white hover:text-indigo-50"
          >
            Services
          </a>
          <!-- escape -->
          <a
            key="Company"
            href="#escape"
            class="text-base lg:text-2xl font-medium text-white hover:text-indigo-50"
          >
            Escape
          </a>
          <!-- arcade -->
          <a
            key="Docs"
            href="#arcade"
            class="text-base lg:text-2xl font-medium text-white hover:text-indigo-50"
          >
            Arcade
          </a>
          <!-- culture -->
          <a
            key="Docs"
            href="#culture"
            class="text-base lg:text-2xl font-medium text-white hover:text-indigo-50"
          >
            Culture
          </a>
        </div>
        <MenuIcon />
      </div>
    </nav>
  </header>
</template>

<script>
export default {}
</script>

<style></style>
