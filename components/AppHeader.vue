<template>
  <div class="border-b border-gray-300 pb-12 pt-10 flex justify-between text-gray-800">
    <div>
      <Logo class="h-10" />
    </div>
    <div class="flex items-center">
      <nav class="ml-6">About</nav>
      <nav class="ml-6">Kontakt</nav>
      <button
        class="bg-white hover:bg-gray-100 text-gray-800 font-semibold py-2 px-4 border border-gray-400 rounded shadow ml-6"
      >Anfrage stellen</button>
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