<template>
  <div class="text-center">
    <div>
      <section class="font-bold text-2xl leading-tight pb-4 pt-10">{{title}}</section>
    </div>
    <div>
      <p class="text-gray-800 text-base leading-tight pb-8">{{subtitle}}</p>
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