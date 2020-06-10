<template>
  <div class="border-b border-gray-300 py-4 pb-12">
    <Headline :title="title" :subtitle="subtitle" />
    <div class="flex items-center w-5/6 mx-auto justify-around">
      <section class="w-1/3">
        <div class="bg-yellow-200 h-64 w-5/6 mx-auto"></div>
      </section>
      <section class="w-2s/3">
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