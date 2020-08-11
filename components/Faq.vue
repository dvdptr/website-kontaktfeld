<template>
  <div class="w-full">
    <Headline :title="title" :subtitle="subtitle" />
    <section class="w-2/3 mx-auto pb-20">
      <VueFaqAccordion :items="myItems" />
    </section>
  </div>
</template>

<script>
import VueFaqAccordion from "vue-faq-accordion";
import Headline from "@/components/elements/Headline";

export default {
  components: {
    VueFaqAccordion,
    Headline
  },
  data() {
    return {
      title: "FAQ",
      subtitle: "Häufig gestellte Fragen rund um das Thema Gestaltberatung.",
      myItems: [
        {
          title:
            "Was ist Gestaltberatung. Oder auch: Ich kann doch gar nicht malen?!",
          value:
            "»Gestaltberatung. Das hört sich schon so nach Malen an«, ist ein Satz, den ich häufig zu hören bekomme. In der Regel folgt darauf: »Ich kann aber gar nicht malen.« Gestaltberatung ist eine Form der Gestalttherapie, die wiederum im 20. Jahrhundert von Fritz Pearls, Laura Pearls und Paul Goodman gegründet worden ist. Das Ehepaar Pearls – beide Psychoanalytiker – verknüpften Erkenntnisse aus der Wahrnehmungspsychologie und Existenzphilosophie in ihrer therapeutischen Arbeit. Aus gestaltpsychologischem Kontext integrierten sie beispielsweise das Figur-Grund-Prinzip. Dieses besagt, dass vor einem wie auch immer gearteten Hintergrund bestimmte Figuren in den Vordergrund treten. Diese Figuren werden auch als offene Gestalten bezeichnet, die wieder in den Hintergrund treten wenn sie geschlossen worden sind. In einen therapeutischen Kontext übertragen bedeutet dies: Vor dem Hintergrund der individuellen Persönlichkeit gibt es Bedürfnisse, die in den Vordergrund drängen und befriedigt werden wollen. Geschieht dies, treten sie wieder in den Hintergrund. Dies können ganz körperliche Bedürfnisse wie Hunger oder Durst sein. Haben wir gegessen oder getrunken, zieht sich dieses Bedürfnis wieder zurück. Bis wir wieder Hunger bekommen und erneut essen. In der Gestalttherapie wird dieser Prozess im Kontaktzyklus beschrieben. Neben diesen grundlegenden körperlichen Bedürfnissen gibt es auch emotionale, soziale oder psychische Gestalten, bspw. Das Bedürfnis nach Liebe, Anerkennung oder Selbstentfaltung. Auch Erinnerungen, Erfahrungen oder Überzeugungen können Gestalten sein. Hier wird die Befriedigung um einiges komplexer und jeder Mensch hat eigene Muster entwickelt, diese Bedürfnisse zu stillen. Aufgrund unserer individuellen Lebensgeschichte sind diese Muster nicht immer oder nicht mehr funktional. Vielleicht schaden sie uns heutzutage sogar oder wir merken, dass das, was früher gut war, heute nicht mehr hilfreich ist. An dieser Stelle setzt Gestalttherapie an. Mithilfe von Experimenten, Ausprobieren und Neu-Gestalten bietet der*die Therapeut*in den Klient*innen die Möglichkeit, im Hier und Jetzt neue Erfahrungen zu machen und in den Prozess der Figur-Grund-Wahrnehmung zu integrieren."
        },
        {
          title: "Wie unterscheidet sich Gestaltberatung von Gestalttherapie?",
          value:
            "Es gibt bis heute unterschiedliche Ansätze, Beratung und Therapie voneinander abzugrenzen. Mir persönlich am eindrücklichsten erschien die Unterscheidung anhand der Zielperson der Intervention. Therapeut*Innen arbeiten mit Patient*innen, Berater*innen mit Klient*Innen (Rahm, xxx). Der Definition von Patient*in oder Klient*In liegt dabei neben anderen das Ausmaß an vorhandenen Ressourcen und empfundenem Leiden auch die Möglichkeiten der Selbstbestimmung zugrunde. </br></br> Eine andere Sichtweise ist der Blick auf Pathologie und Gesundheitssystem. Wer an einer nach Katalogen definierten Krankheit leidet, bekommt Therapie. Beraten wird, wer zu einer bestimmten Fragestellung auf der Suche nach Veränderungen ist und diese Fragestellung nicht alleine beantworten kann oder will.</br></br> Als Gestalttherapeutin verstehe ich mich als Begleiterin auf Augenhöhe. Gemeinsam besprechen wir Ihre persönlichen Ziele. Um diese zu erreichen, stelle ich mein Methodenköfferchen zur Verfügung und habe Ideen, wie im Prozess die Leitplanken verlaufen könnten. Expert*in für sich selbst ist jedoch in jedem Fall der*die Klient*in. Dies gilt sowohl im therapeutischen, als auch beraterischen Setting."
        },
        {
          title: "Was ist das Besondere an analytischer Gestalttherapie?",
          value:
            "Gestalttherapie bedeutet das Erleben, Ausprobieren und Lernen im Hier und Jetzt. Alles Erleben hat Auswirkungen auf die Zukunft und wurzelt in der Vergangenheit. In der analytischen Gestaltarbeit kommt der Bedeutung früher Erfahrungen aus der Kindheit eine besondere Bedeutung zu. Dabei geht es jedoch NICHT um eine Interpretation kindlicher Erlebnisse durch die Therapeutin! Auch eine Durcharbeitung bestimmter Sequenzen ist nicht zwangsläufig Teil der gestalttherapeutischen Arbeit. Durch Bewusstwerden, Wahrnehmen und Anerkennen bestimmter in der Kindheit geprägter Muster können neue Erfahrungen möglich gemacht und unerwünschte Verhaltensmuster abgelegt werden."
        },
        {
          title: "Wie lange wird das dauern? ",
          value:
            "Das kommt ganz auf Ihr Anliegen an! Neben konkreten Fragestellungen der Kurzberatung, Beratung im beruflichen oder sozialen Kontext (i.d.R 3-10 Sitzungen), über die Verarbeitung von Gefühle wie Trauer, Angst, Wut oder Scham beispielsweise in der Trauerbegleitung (10-30 Sitzungen) bis hin zu tiefgehenden Prozessen der Selbsterfahrung und Entwicklung innerer Potentiale, die sich über einen Zeitraum von ein bis zwei Jahren spannen können, ist alles möglich. Wichtig ist hierbei der regelmäßige Abgleich des Prozesses mit Ihren individuellen Bedürfnissen, die Formulierung von Etappenzielen und die Möglichkeit, den Prozess an fast jeder Stelle gemeinsam in befriedigender Form abzuschließen oder zu unterbrechen. </br></br> Gestaltprozesse verlaufen individuell. Jeder Mensch entwickelt sich in seinem*ihrem eigenen Tempo. Daher bestimmen Sie in unserer Arbeit weitestgehend die Geschwindigkeit und Intensität. Ich verzichte in meiner Arbeitsweise weitgehend auf drängende Konfrontation und vorgegebene Deutungen, da ich der Überzeugung bin, dass ein respektvoller und unterstützender Umgang miteinander förderlich für Bearbeitung innere Konflikte, tiefer Gefühle und Ängste ist. </br></br> Je nach Vorstellungen, Möglichkeiten und Ressourcen sind Termine in wöchentlichem oder zweiwöchentlichem Rhythmus ebenso möglich wie größere Abstände. "
        },
        {
          title: "Was kostet das?",
          value:
            "Eine Sitzung (50-60 Minuten) kostet derzeit 60€ inkl. ggf. benötigter Materialien. Für die erste Kennenlernstunde berechne ich 50€. Es ist möglich, Sitzungen im 3er-Paket* für 150€ zu buchen. "
        }
      ]
    };
  }
};
</script>

<style></style>
