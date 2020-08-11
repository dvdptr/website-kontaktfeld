<template>
  <div class>
    <AppHeader />
    <Faq />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "~/components/AppHeader";
import AppFooter from "~/components/AppFooter";
import Faq from "~/components/Faq";

export default {
  components: {
    AppHeader,
    Faq,
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
