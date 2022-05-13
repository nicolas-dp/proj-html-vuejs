<template>
    <header>
        <div class="container-fluid">
            <div class="logo">
                LOGO
            </div>
            <Navbar :link="link" v-for="(link, index) in links" :key="index"/>
        </div>
    </header>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: "SiteHeader",
  components: {
      Navbar
  },

  data() {
    return {
      links: ['Home', 'Culinary History', 'Our Team', 'Our Menu', 'Takeout', 'Bulletin', 'Reservation', 'Carrello'],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
</style>