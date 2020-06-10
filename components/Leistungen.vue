<template>
  <div class="border-b border-gray-300 pb-12">
    <Headline :title="title" :subtitle="subtitle" />
    <div class="flex flex-wrap justify-around text-center">
      <div v-for="leistung in leistungenOverview" v-bind:key="leistung" class="w-1/2 pb-16 px-10">
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
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, ipsam odio? Odit illum omnis cupiditate voluptas dolor provident fuga vero."
        },
        {
          leistung: "Kreative Methoden",
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, ipsam odio? Odit illum omnis cupiditate voluptas dolor provident fuga vero."
        },
        {
          leistung: "Körperorientierte Methoden (Tanzpädagogik)",
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, ipsam odio? Odit illum omnis cupiditate voluptas dolor provident fuga vero."
        },
        {
          leistung: "Prozessbegleitung im Jahreskreis",
          text:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, ipsam odio? Odit illum omnis cupiditate voluptas dolor provident fuga vero."
        }
      ]
    };
  }
};
</script>

<style>
</style>
