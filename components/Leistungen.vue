<template>
  <div class="border-b border-gray-300 pb-12">
    <Headline :title="title" :subtitle="subtitle" />
    <div class="flex flex-wrap justify-around text-center">
      <div v-for="leistung in leistungenOverview" v-bind:key="leistung" class="w-1/3 pb-10">
        <section class="font-bold">{{leistung.leistung}}</section>
        <section class="text-gray-800">{{leistung.text}}</section>
      </div>
    </div>
  </div>
</template>

<script>
import Headline from "@/components/elements/Headline.vue";

export default {
  components: {
    Headline
  },
  data() {
    return {
      title: "Methoden im Überblick",
      subtitle: "Unsere Leistungen und Angebote",
      leistungenOverview: [
        {
          leistung: "Gestaltberatung",
          text: "text zu eins"
        },
        {
          leistung: "Kreative Methoden",
          text: "text zu zwei"
        },
        {
          leistung: "Körperorientierte Methoden (Tanzpädagogik)",
          text: "text zu 3"
        },
        {
          leistung: "Prozessbegleitung im Jahreskreis",
          text: "text zu 4"
        },
        {
          leistung: "Kreative Methoden",
          text: "text zu 5"
        }
      ]
    };
  }
};
</script>

<style>
</style>
