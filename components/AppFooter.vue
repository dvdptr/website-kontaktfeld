<template>
  <div class="py-8 text-sm text-gray-800 bg-gray-300">
    <div class="flex justify-evenly">
      <!-- <div class="leading-tight font-bold">
        <p>Simone Ebner</p>
        <p>Raum für Gestaltberatung</p>
      </div>-->
      <Logo class="h-8" />
      <div class>
        <p class="underline">Anschrift</p>
        <p>Paulinstr. 75</p>
        <p>54292 Trier</p>
      </div>
      <div class>
        <p class="underline">Kontakt</p>
        <p>Telefon: 9876</p>
        <p>e-Mail: se@gestaltberatung-trier.de</p>
      </div>
    </div>
    <div class="text-center pt-6 text-sm text-gray-600">
      <p>c Trier, 2020 | Impressum</p>
    </div>
  </div>
</template>

<script>
import Logo from "@/components/Logo.vue";
export default {
  components: {
    Logo
  }
};
</script>

<style>
</style>