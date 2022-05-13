<template>
  <header>
    <div class="jumbo">
      <nav class="navbar">
        <div class="container">
          <LogoComponent />
          <ul class="navbar-nav flex-row">
            <Navbar :link="link" v-for="link in links" :key="link.id" />
          </ul>
        </div>
      </nav>
      <div class="jumbo_text container">
        <h3 class="text-white">Mio Testo</h3>
      </div>
    </div>
  </header>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import LogoComponent from "@/components/LogoComponent.vue"
export default {
  name: "SiteHeader",
  components: {
    Navbar,
    LogoComponent,
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

nav {
  font-size: 15px;
  li {
    padding: 0.5rem;
  }
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

.jumbo_text {
  width: 40%;
}
</style>