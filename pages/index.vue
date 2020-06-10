<template>
  <div>
    <AppHeader />
    <Hero />
    <Leistungen />
    <AboutGestaltberatung />
    <Fragen />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "~/components/AppHeader";
import Hero from "~/components/Hero";
import Leistungen from "~/components/Leistungen";
import AboutGestaltberatung from "~/components/AboutGestaltberatung";
import Fragen from "~/components/Fragen";
import AppFooter from "~/components/AppFooter";

export default {
  components: {
    AppHeader,
    Hero,
    Leistungen,
    AboutGestaltberatung,
    Fragen,
    AppFooter
  }
};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
