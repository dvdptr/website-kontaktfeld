<template>
  <div class>
    <AppHeader />
    <AboutSE />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "~/components/AppHeader";
import AboutSE from "~/components/AboutSE";

import AppFooter from "~/components/AppFooter";

export default {
  components: {
    AppHeader,
    AboutSE,
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
