<template>
  <div class="py-8 text-gray-800">
    <div class="flex w-5/6 justify-between mx-auto">
      <div>
        <nuxt-link to="/">
          <Logo class="h-10" />
        </nuxt-link>
      </div>
      <div class="flex items-center">
        <nav class="ml-6">
          <nuxt-link to="/about">About</nuxt-link>
        </nav>

        <nav class="ml-6">
          <nuxt-link to="/kontakt">Kontakt</nuxt-link>
        </nav>
        <button
          class="bg-white hover:bg-gray-100 text-gray-800 font-semibold py-2 px-4 border border-gray-400 rounded shadow ml-6"
        >Anfrage stellen</button>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "@/components/Logo";
export default {
  components: {
    Logo
  }
};
</script>

<style>
</style>