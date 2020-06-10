<template>
  <div class="container">
    <AppHeader />
    <Kontakt />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "~/components/AppHeader";
import Kontakt from "~/components/Kontakt";

import AppFooter from "~/components/AppFooter";

export default {
  components: {
    AppHeader,
    Kontakt,
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
