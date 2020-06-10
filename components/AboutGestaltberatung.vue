<template>
  <div class="border-b border-gray-300 pb-12">
    <Headline :title="title" :subtitle="subtitle" />
    <section>
      <p class="w-2/3 mx-auto text-2xl">{{about}}</p>
    </section>
  </div>
</template>

<script>
import Headline from "~/components/elements/Headline";
export default {
  components: { Headline },
  data() {
    return {
      title: "About Gestaltberatung",
      subtitle: "Subtext",
      about:
        "Es gibt Zeiten im Leben, in denen man sich ein offenes Ohr wünscht. Eine freundliche und friedliche Umgebung. Kleine Pausen vom alltäglichen Funktionieren, Müssen und dem allgemeinen Einerlei. Vielleicht fragen Sie sich auch: Das soll es jetzt nun also sein? Wir spüren, dass da noch mehr ist im Leben, dass da mehr sein könnte. Während Ihres Prozesses unterstütze ich Sie dabei, ihr Potential zu entfachen. Hin zu mehr Lebendigkeit und Lebensfreude. Im Raum für Gestaltberatung werden Sie auf Ihrem individuellen Prozess in geschütztem Rahmen begleitet. Unabhängig von institutionellen Vorgaben, pathologisierenden und aktenkundigen Diagnosen und Höchststundenzahlen haben Sie die Freiheit, Ihren eigenen Raum zu schaffen, indem sich ihr Prozess kreativ und in Ihrem eigenen Tempo entfalten kann."
    };
  }
};
</script>

<style>
</style>