<template>
  <div class="text-center">
    <div>
      <section class="font-bold text-3xl leading-tight pb-4 pt-12">{{title}}</section>
    </div>
    <div>
      <p class="text-gray-800 text-base leading-tight pb-16">{{subtitle}}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: ["title", "subtitle"]
};
</script>

<style>
</style>