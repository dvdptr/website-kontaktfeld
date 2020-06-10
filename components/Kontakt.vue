<template>
  <div class="border-b border-gray-300 py-4">
    <Headline :title="title" :subtitle="subtitle" />
    <div class="flex items-center">
      <section class="w-1/3">
        <div class="bg-yellow-200 h-64 w-56 mx-auto"></div>
      </section>
      <section class="w-2s/3">
        <p>Kontakt</p>
        <p>Paulinstr. 75</p>
        <p>54292 Trier</p>
        <br />
        <p>Telefon: 9876</p>
        <p>e-Mail: se@gestaltberatung-trier.de</p>
      </section>
    </div>
  </div>
</template>

<script>
import Headline from "@/components/elements/Headline";

export default {
  components: {
    Headline
  },
  data() {
    return {
      title: "Kontakt",
      subtitle:
        "Sie erreichen uns unter folgenden Angaben. Wir freuen uns von Ihnen zu hören!"
    };
  }
};
</script>

<style>
</style>