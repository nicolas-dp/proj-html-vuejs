<template>
  <header>
    <div class="container">
      <nav class="navbar">
        <div class="logo">
          <img src="@/assets/img/logo-restaurant.png" alt="logo" />
        </div>
        <ul class="navbar-nav flex-row">
          <Navbar :link="link" v-for="link in links" :key="link.id" />
        </ul>
      </nav>
    </div>
    <div class="jumbo"></div>
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
        {
          id: 1,
          text: "Home",
          icon: "",
        },
        {
          id: 2,
          text: "Culinary History",
          icon: "",
        },
        {
          id: 3,
          text: "Our Team",
          icon: "",
        },
        {
          id: 4,
          text: "Our Menu",
          icon: "",
        },
        {
          id: 5,
          text: "Takeout",
          icon: "",
        },
        {
          id: 6,
          text: "Bulletin",
          icon: "",
        },
        {
          id: 7,
          text: "Reservation",
          icon: "",
        },
        {
          id: 8,
          text: "",
          icon: '<font-awesome-icon icon="fa-solid fa-cart-shopping" />',
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
header {
  background-color: black;
}
.navbar {
  /* position: fixed; */
  background-color: rgba(0, 0, 0, 0.301);
}

.jumbo {
  background-image: url("@/assets/img/slider52x.jpg");
  height: 100vh;
  background-position: right;
  background-repeat: no-repeat;
  background-size: contain;
}
</style>