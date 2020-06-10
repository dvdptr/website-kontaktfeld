<template>
  <div class="w-5/6 mx-auto border-b border-gray-300 pb-12">
    <Headline :title="title" :subtitle="subtitle" />
    <div class="flex flex-wrap justify-around text-center">
      <div
        v-for="leistung in leistungenOverview"
        v-bind:key="leistung"
        class="w-1/2 mb-16 p-10 shadow-none hover:shadow-md rounded-md"
      >
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
