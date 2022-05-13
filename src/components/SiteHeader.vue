<template>
  <header>
    <div class="container navigation">
      <div class="logo"><img src="@/assets/img/logo-restaurant.png" alt="logo"></div>
      <nav class="navbar">
        <ul class="navbar-nav flex-row">
          <Navbar :link="link" v-for="(link, index) in links" :key="index" />
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
export default {
  name: "SiteHeader",
  components: {
    Navbar,
  },

  data() {
    return {
      links: [
        "Home",
        "Culinary History",
        "Our Team",
        "Our Menu",
        "Takeout",
        "Bulletin",
        "Reservation",
        "Carrello",
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
header{
    background-color: rgba(21, 21, 21, 0.66);
}

.navigation {
  display: flex;
  flex-wrap: wrap;
  align-content: center;
  align-items: center;
  justify-content: space-between;
}


</style>