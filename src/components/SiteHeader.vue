<template>
  <header>
    <div class="jumbo">
      <nav class="navbar">
        <div class="container">
          <!-- Componente Logo -->
          <LogoComponent />
          <ul class="navbar-nav flex-row">
            <!-- Creazione dinamica dei link presenti nella navbar -->
            <Navbar :link="link" v-for="link in links" :key="link.id" />
          </ul>
        </div>
      </nav>
      <JumboFirst />
    </div>
  </header>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import LogoComponent from "@/components/LogoComponent.vue";
import JumboFirst from "@/components/JumboFirst.vue";
export default {
  name: "SiteHeader",
  components: {
    Navbar,
    LogoComponent,
    JumboFirst,
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
  background-color: rgb(0 0 0 / 68%);
  position: fixed;
  top: 0px;
  width: 100%;
  z-index: 1;
}

.jumbo {
  background-image: url("@/assets/img/slider52x.jpg");
  background-position: right;

  background-repeat: no-repeat;
  background-size: 60%;
}
</style>