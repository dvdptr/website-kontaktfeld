<template>
  <div class="border-b border-gray-300 py-4">
    <Headline :title="title" :subtitle="subtitle" />
    <div class="flex items-center">
      <section class="w-1/3">
        <div class="bg-yellow-200 h-64 w-56 mx-auto"></div>
      </section>
      <section class="w-2/3">
        <p>VITA</p>
        <p>Simone Ebner, geboren 1985 in Trier</p>
        <p>Seit 2017 Analytische Gestalttherapeutin i.A.</p>
        <p>Seit 2015 Mitarbeiterin im Psychosozialen Zentrum für Flüchtlinge, Trier</p>
        <p>2015 Abschluss des M.Sc. Psychologie (Universität Trier)</p>
        <p>2004-2009 Ausbildung zur Buchhändlerin</p>
        <p>Seit 2012 Mutter eines Sohnes</p>
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
      title: "About Simone Ebner",
      subtitle: "Text subtext"
    };
  }
};
</script>

<style>
</style>