<template>
  <div class="border-b border-gray-300 py-12 text-sm text-gray-700">
    <div class="flex justify-evenly">
      <div>
        <Logo class="h-8" />
      </div>
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
    <div class="text-center pt-12 text-sm text-gray-600">
      <p>c Trier, 2020 | Impressum</p>
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