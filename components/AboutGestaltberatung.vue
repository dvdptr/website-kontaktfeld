<template>
  <div class="border-b border-gray-300 pb-12">
    <Headline :title="title" :subtitle="subtitle" />
  </div>
</template>

<script>
import Headline from "~/components/elements/Headline";
export default {
  components: { Headline },
  data() {
    return {
      title: "About Gestaltberatung",
      subtitle: "Subtext"
    };
  }
};
</script>

<style>
</style>