<template>
  <div id="app">
    <!-- Site Header -->
    <SiteHeader />
    <!-- Site Main -->
    <SiteMain />
    <!-- Site footer -->
    <SiteFooter />
    <!-- Copyright -->
    <CopyRight />
  </div>
</template>

<script>
import SiteHeader from "@/components/SiteHeader.vue";
import SiteMain from "@/components/SiteMain.vue";
import SiteFooter from "@/components/SiteFooter.vue";
import CopyRight from "@/components/CopyRight.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
    CopyRight,
  },

};
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
@import url("https://fonts.googleapis.com/css2?family=Montaga&display=swap");
</style>
